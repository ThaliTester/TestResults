#### Test 50650278bcecc5c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  909): acquireWL(4376c3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10074}
V/AlarmManager(  909): sending alarm PendingIntent{42590818: PendingIntentRecord{42564580 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450461132805, Int=0
I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4483 uid=10078 gids={50078}
V/AlarmManager(  909): sending alarm PendingIntent{41fdd1d8: PendingIntentRecord{41fdd1a0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450461137929, Int=60000
D/PMS     (  909): releaseWL(4376c3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
--------- beginning of /dev/log/main
D/SMSBackup( 4483): SMSBackupAgentService started
D/SMSBackup( 4483): Checking restore status
D/SMSBackup( 4483): Restore complete
D/SMSBackup( 4483): cancelCheckAlarm
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
D/SMSBackup( 4483): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/Finsky  ( 4194): [437] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4194): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  909): killProcessQuiet, pid=3900
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3900:com.google.android.music:main/u0a154 (adj 15): empty #17
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3900
D/MediaRouterService(  909): Client com.google.android.music (pid 3900): Died!
E/cutils-trace( 4496): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4496): ====startRecUseTime====
D/htc.customization.log.level( 4496):  is 
W/CustomizationLogLevel( 4496): Level value is invalid, use default level 2
I/ActivityManager(  909): Waited long enough for: ServiceRecord{435fb630 u0 com.htc.htclocationservice/.AutoSettingService}
D/CustomizationManager( 4496):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4496): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4496): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4496): Parsing tag category name = system
I/CustomizationCIDLoader( 4496): Parsing tag category name = application
I/CustomizationCIDLoader( 4496): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4496): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4496): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4496): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4496): Parsing tag category name = Settings
D/CustomizationManager( 4496):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4496):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 4496): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4496): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4496): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4496): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4496
D/PMS     (  909): acquireHCC(4236dd90): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(422e96a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
W/asset   (  909): Copying FileAsset 0x68a40fb8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1111153048
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cab848
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
D/PMS     (  909): acquireWL(41a810e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4507 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
W/asset   ( 4507): Copying FileAsset 0x5c7db428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/LightsService(  909): setLight #0: color=#23
V/WebViewChromiumFactoryProvider( 4507): Binding Chromium to main looper Looper (main, tid 1) {41a6af68}
I/LibraryLoader( 4507): Expected native library version number "",actual native library version number ""
I/chromium( 4507): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4507): Initializing chromium process, renderers=0
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424b7bc8:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4507): 1101532872: getState(). Returning 12
D/PMS     (  909): acquireWL(42139208): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  909): acquireWL(41fa5c30): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  909): releaseWL(41fa5c30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4507): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4507): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4507): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4507): Local Branch: 
I/Adreno-EGL( 4507): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4507): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4507):                  aa63bbd948f41d15fc72f585e
V/LightsService(  909): setLight #0: color=#20
V/LightsService(  909): setLight #0: color=#19
W/chromium( 4507): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4507): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4507): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4507): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4507): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4507): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4507): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4507): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4507): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4507): CordovaWebView is running on device made by: HTC
V/LightsService(  909): setLight #0: color=#14
,W/AwContents( 4507): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Disable input method client, pid=1275
,W/ResourceType( 4507): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4507): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ab2578, mServedView=org.apache.cordova.engine.SystemWebView{41a781e0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4507): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Enable input method client, pid=4507
I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +295ms
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  909): releaseWL(41a810e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/JsMessageQueue( 4507): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4507): JniHelper::setJavaVM(0x41543048), pthread_self() = 1661963216
,D/JX-Cordova( 4507): jxcore cordova android initializing
,I/dalvikvm-heap( 4507): Grow heap (frag case) to 11.601MB for 144892-byte allocation
,I/dalvikvm-heap( 4507): Grow heap (frag case) to 11.719MB for 217334-byte allocation
,I/dalvikvm-heap( 4507): Grow heap (frag case) to 11.894MB for 325996-byte allocation
,I/dalvikvm-heap( 4507): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,I/dalvikvm-heap( 4507): Grow heap (frag case) to 12.574MB for 733480-byte allocation
,I/dalvikvm-heap( 4507): Grow heap (frag case) to 14.079MB for 1650320-byte allocation
,I/dalvikvm-heap( 4507): Grow heap (frag case) to 15.442MB for 2475476-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(4236dd90): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(422e96a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4507): Grow heap (frag case) to 17.470MB for 3713210-byte allocation
,W/jxcore-log( 4507): Initializing JXcore engine
,W/jxcore-log( 4507): JXcore engine is ready
,W/jxcore-log( 4507): Starting JXcore engine
,W/jxcore-log( 4507): Platform android
W/jxcore-log( 4507): 
,W/jxcore-log( 4507): Process ARCH arm
W/jxcore-log( 4507): 
,D/PMS     (  909): releaseWL(42139208): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4507): JXcore Cordova bridge is ready!
I/jxcore-log( 4507): 
,W/jxcore-log( 4507): JXcore engine is started
,I/chromium( 4507): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/jxcore-log( 4507): Toggling radios to true
I/jxcore-log( 4507): 
,D/BluetoothAdapter( 4507): enable(): BT is already enabled..!
,D/WifiManager( 4507): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 919
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
,W/Settings:Agent(  909): << traceCallingStack(): 1(ms)
D/WifiManager( 4507): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  909): doBoolean: DISCONNECT
D/WifiManager( 4507): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiService(  909): New client listening to asynchronous messages
D/WifiService(  909): setWifiEnabled: true pid=4507, uid=10389
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/wpa_supplicant( 1185): TDLS: Tear down peers
I/wpa_supplicant( 1185): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4507): Radios toggled
I/jxcore-log( 4507): 
D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4507): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4507): 
I/jxcore-log( 4507): Perf Test app loaded loaded
I/jxcore-log( 4507): 
I/Choreographer( 4507): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4507): check test folder
I/jxcore-log( 4507): 
,I/jxcore-log( 4507): found test : ./testFindPeers.js
I/jxcore-log( 4507): 
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1185): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1185): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8eebbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1185): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 48 (NL80211_CMD_DISCONN,ECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  909):    returned true
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
,D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
,D/Tethering(  909): interfaceStatusChanged wlan0, false
,I/jxcore-log( 4507): found test : ./testSendData.js
I/jxcore-log( 4507): 
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  909): acquireWL(43bdcd40): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  909): doBoolean: RECONNECT
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): Fast associate: Old scan results
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20383 mDataStallAlarmIntent=PendingIntent{42573a98: PendingIntentRecord{423f9ac8 android broadcastIntent}}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/UsbnetStateTracker(  909): isAvailable+-
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/WifiService(  909): New client listening to asynchronous messages
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1356): Read error: ssl=0x63f30008: I/O error during system call, Connection timed out
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/libc    (  365): [NET] entry_id:3   entry:0xb7783590  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb77832a8  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb7787e40  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb7787d90  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb7787f70  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb777ec20  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb7783458  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb77831b8  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x63f30008: I/O error during system call, Broken pipe
D/PMS     (  909): acquireWL(425c4c58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(437779c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SCAN
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1185): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/BatSI   (  909): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  909):    returned false
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/PMS     (  909): releaseWL(425c4c58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/PMS     (  909): releaseWL(437779c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
,I/chromium( 4507): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  909): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4559 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(43fc85c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.,
D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/PMS     (  909): releaseWL(43fc85c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4338/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4338/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,I/MusicStore( 4559): Database version: 95
,W/ContextImpl( 4559): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4559): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4559): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4559): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4559): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4559, uid=10154, userID:0
,D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,D/MediaRouterService(  909): Client com.google.android.music (pid 4559): Registered
,I/MediaRouter( 4559): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.music (4559/10154)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2366/10021)
,I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4579 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4559): getSelectedRoute
,I/NetworkMonitor( 4559): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4559/10154)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4559, uid=10154, userID:0
,D/PMS     (  909): acquireWL(44053e08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/Process (  909): killProcessQuiet, pid=3882
D/PMS     (  909): releaseWL(44053e08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  909): Killing 3882:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ACRA    ( 4579): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4579): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4579): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  909): Recipient 3882
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4579): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4579): Preparing secondary program dexes.
V/DexLibLoader( 4579): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4579): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4579): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4579): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4579): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4579): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4579): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4579): Dex already copied
D/OdexVerifier( 4579): Odex verification is skipped.
,V/DexLibLoader( 4579): Creating class loader
,V/DexLibLoader( 4579): Finished creating class loader
V/DexLibLoader( 4579): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4579): Dex already copied
D/OdexVerifier( 4579): Odex verification is skipped.
,V/DexLibLoader( 4579): Creating class loader
,V/DexLibLoader( 4579): Finished creating class loader
V/DexLibLoader( 4579): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4579): Dex already copied
D/OdexVerifier( 4579): Odex verification is skipped.
,V/DexLibLoader( 4579): Creating class loader
,V/DexLibLoader( 4579): Finished creating class loader
V/DexLibLoader( 4579): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4579): Dex already copied
D/OdexVerifier( 4579): Odex verification is skipped.
,V/DexLibLoader( 4579): Creating class loader
,V/DexLibLoader( 4579): Finished creating class loader
,V/DexLibLoader( 4579): Verifying classes from secondary dexes.
,D/DexLibLoader( 4579): DexLibLoader.ensureDexLoaded took 22 ms
,W/dalvikvm( 4579): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1185): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1185): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1185): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1185): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1185): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1185): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 1
I/wpa_supplicant( 1185): wpa_s->is_screen_on 1
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doStri,ng: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
,D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1185): reply (489) for get BSS: id=0
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000104791089
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=1
I/wpa_supplicant( 1185): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-62
I/wpa_supplicant( 1185): tsf=0000000104791101
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1185): ssid=01ABC
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-62
I/wpa_supplicant( 1185): tsf=0000000104791105
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=3
,I/wpa_supplicant( 1185): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1185): freq=2427
I/wpa_supplicant( 1185): level=-79
I/wpa_supplicant( 1185): tsf=0000000104791109
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=Gonzos
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList,
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 104791089, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiStateMachine(  909): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -62, frequency: 2412, timestamp: 104791101, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 104791105, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 104791109, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1185): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Add randomness: count=11 entropy=4
I/wpa_supplicant( 1185): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1185): TDLS: Remove peers on association
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1185): EAPOL: enable timer tick
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1185): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): Get randomness: len=32 entropy=5
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiStateMachine(  909): Associated
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
,D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..,
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8eec9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6edcb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    broadcast key
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1185): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1185): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1185): set send_ind_to_ndc = 0
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1185): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1185): EAPOL authentication completed successfully
I/wpa_supplicant( 1185): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
,D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/DhcpStateMachine(  909): [StoppedState] Start DHCP
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 1
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  909):    returned null
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(43798da0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42491200 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42491200 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/SensorManager(  909): mEventCount = 900
,W/dalvikvm( 4579): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4579): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42169278
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42169278, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b719c0
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@42288e08
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  909): mWirelessDisplayManager is null
,W/fb4a(:<default>):StaticBindingVerifier( 4579): Verify
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 319ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43828530)
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/PMS     (  909): OOBE c monitor 11
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=4507
,D/PMN     (  909): wakingUp
I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1260): ScreenObserver: OFF
D/NfcService( 1260): applyRouting - 0
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
W/ResourceType( 4507): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4507): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a781e0 VFEDH.C. .F...... 0,0-720,1134 #64}
I/WindowManager(  909): No lock screen! windowToken=null
D/WifiService(  909): New client listening to asynchronous messages
,D/NfcService( 1260): applyRouting -2
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  909): acquireWL(4261b5e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
D/PMS     (  909): acquireWL(432c5868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMN     (  909): onScreenOn
D/PMS     (  909): releaseWL(432c5868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): releaseWL(4261b5e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/MtpService( 2366): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2366): [MTP][onReceive]-
,D/NfcService( 1260): applyRouting - 0
,D/NfcService( 1260): applyRouting -2
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): acquireWL(44013f98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
,D/PMS     (  909): releaseWL(44013f98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/ClockThread( 1118): stop update clock
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1185): Change stage from stage0 to stage3
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 24
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): SET_SCREEN_ON:On
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,V/SRS_Proc(  372): ParamSet string: screen_state=on
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  909): updateScreenOn: false
,W/fb4a(:<default>):BaseAnalyticsConfig( 4579): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4579): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): acquireWL(436cd848): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(436cd848): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4388e3a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4388e3a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/dalvikvm-heap( 4579): Grow heap (frag case) to 9.511MB for 73240-byte allocation
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1785): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1785): onScreenOn: 1450461146592
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1785): onScreenOn: 1450461146593
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b719c0
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b719c0, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@42288e08
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/Process (  909): killProcessQuiet, pid=4108
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMN     (  909): goingToSleep
I/ActivityManager(  909): Killing 4108:com.google.android.talk/u0a111 (adj 15): empty #17
D/PMS     (  909): acquireWL(436ad138): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/PMS     (  909): releaseWL(436ad138): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20384 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): SET_SCREEN_ON:Off
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1185): get_ip_address source addr = 02000000
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  909):    returned true
I/ActivityManager(  909): Recipient 4108
D/PMS     (  909): acquireWL(425d2148): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
,D/PMS     (  909): releaseWL(425d2148): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
V/SRS_Proc(  372): ParamSet string: screen_state=off
D/AutoSetting( 1326): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4615 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
,D/NetworkPolicy(  909): updateScreenOn: false
,D/AutoSetting( 1326): Util - no network available!
,D/ContactMessageStore( 1247): start background delete task...
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
D/AutoSetting( 1326): service - onCreate()
D/AutoSetting( 1326): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  909): request 42389730 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1326): service - mHandler: cancel location update
D/AutoSetting( 1326): service -           changes count: 0
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,W/fb4a(:<default>):UserScope( 4579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 4579): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
,D/MobileConnectivityChangeReceiver( 4615): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4615): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4615): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4615): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/PMS     (  909): acquireWL(435cfe80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
,D/PMS     (  909): releaseWL(435cfe80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/fb4a(:<default>):UserScope( 4579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4633 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
,D/PMS     (  909): acquireWL(438f4b38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
,D/PMS     (  909): releaseWL(438f4b38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1185): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1185): EAPOL: disable timer tick
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1785): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1785): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1785): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1785): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1785): onScreenOff
,I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4649 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=4307
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  909): Killing 4307:com.google.android.partnersetup/u0a32 (adj 15): empty #17
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4579): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/ActivityManager(  909): Recipient 4307
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 9.956MB for 84664-byte allocation
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4579): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4579): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4579): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4579): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4649): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4649): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4649): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4649): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 9.971MB for 28144-byte allocation
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4579): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4579): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4579): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4579): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4579): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4579): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4579): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4579): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/ContextImpl( 4649): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 10.013MB for 39954-byte allocation
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 10.088MB for 79892-byte allocation
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
,V/WebViewChromiumFactoryProvider( 4649): Binding Chromium to main looper Looper (main, tid 1) {41a701b8}
I/LibraryLoader( 4649): Expected native library version number "",actual native library version number ""
I/chromium( 4649): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4649): Initializing chromium process, renderers=0
,D/PMS     (  909): acquireWL(4357a0f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  909): acquireWL(4361be78): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4649): BLUETOOTH permission is missing!
D/PMS     (  909): releaseWL(4357a0f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4649): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4649): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4649): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4649): Local Branch: 
I/Adreno-EGL( 4649): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4649): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4649):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4649): Starting up...
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 10.276MB for 75760-byte allocation
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43556038 u0 ReceiverList{43555f18 4579 com.facebook.katana/10027/u0 remote:440f1960}}
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43556038 u0 ReceiverList{43555f18 4579 com.facebook.katana/10027/u0 remote:440f1960}}
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424da1b8 u0 ReceiverList{424da158 4579 com.facebook.katana/10027/u0 remote:430cad78}}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/Process (  909): killProcessQuiet, pid=4338
,I/ActivityManager(  909): Killing 4338:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4338
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/iu.Environment( 2189): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
I/iu.UploadsManager( 2189): num queued entries: 0
I/iu.UploadsManager( 2189): num updated entries: 0
I/iu.SyncManager( 2189): NEXT; no task
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/AutoSetting( 1326): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 3846): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3846): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3846): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3846): Cust_ConnectToPC   : spcsc>false
D/        ( 3846): Cust_ConnectToPC   : IPT>true
D/        ( 3846): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3846): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3846): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3846): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3846): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
I/PSReceiver( 3846): onReceive:android.intent.action.USER_PRESENT
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ContextImpl( 3846): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3846): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3846): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3846):  defaultType:0
,D/PMS     (  909): acquireWL(4402b7b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4701 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  909): releaseWL(4402b7b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(43798da0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): gateway: /192.168.1.1
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
,D/SmartSyncUtils( 4701): isEpsOn(), nState = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  909): acquireWL(43c07750): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4701 1000 null
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  909): WAN detection
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WISPrService( 3846): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@423f1f80
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/PMS     (  909): releaseWL(43c07750): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  909): acquireWL(438774a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4701): getMobilePolicyEnabled, result = true
D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  909): killProcessQuiet, pid=4362
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I/ActivityManager(  909): Killing 4362:com.htc.backup/1000 (adj 15): empty #17
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  909): acquireWL(4230a4c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Recipient 4362
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(41ff96e0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1450461099328 min interval config: 0 actual interval: 48248
D/PMS     (  909): releaseWL(4230a4c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/SmartSyncUtils( 4701): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4701): getMobilePolicyEnabled, result = true
I/CheckinService( 2189): Checking schedule, now: 1450461147588 next: 1450461129300
I/CheckinService( 2189): active receiver: enabled
,D/SmartSyncUtils( 4701): isEpsOn(), nState = 0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2189, uid=10029, userID:0
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42288e08
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42288e08, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42288e08, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42288e08
D/WifiService(  909): New client listening to asynchronous messages
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/CheckinService( 2189): Preparing to send checkin request
,I/EventLogService( 2189): Accumulating logs since 1450461093902
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41d56fc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41d56fc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): releaseWL(438774a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4742 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4742): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4742): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4742): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4742): install
,I/MultiDex( 4742): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4742): loading existing secondary dex files
,I/MultiDex( 4742): load found 3 secondary dex files
,I/MultiDex( 4742): install done
,W/dalvikvm( 4742): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4742): VFY: unable to resolve instance field 36
,W/dalvikvm( 4742): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4742): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4742): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4742): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4742): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1226): callingUid 10029, callindPid: 1226
,W/dalvikvm( 4742): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4742): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4742): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4742): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4742): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2189): Restart initialization of location
,D/AuthorizationBluetoothService( 1356): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1356): Proximity feature is not enabled.
,E/MDM     ( 1226): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1226): No location to return for getLastLocation()
,W/FusedLocationProvider( 1226): location=null
D/PMS     (  909): acquireWL(422deba8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(422deba8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4742): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1741431386
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4507): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4507): threadid=1: thread exiting with uncaught exception (group=0x4163be30)
D/PMS     (  909): releaseWL(43bdcd40): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,E/ActivityManager(  909): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4507): FATAL EXCEPTION: main
E/AndroidRuntime( 4507): Process: com.test.thalitest, PID: 4507
E/AndroidRuntime( 4507): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4507): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4507): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4507): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4507): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4507): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4507): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4507): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4507): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4507): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4507): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4507): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4507): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4507): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4507): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4507): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4507): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4507): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4507): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  909):   Force finishing activity com.test.thalitest/.MainActivity
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Process (  909): killProcessQuiet, pid=4380
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  909): Killing 4380:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Process ( 4507): killProcess, pid=4507
D/Process ( 4507): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
V/Tethering(  909): bSetPropertyMultiRAB:false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3961/10053)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/InputDispatcher(  909): channel '422c6808 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  909): channel '422c6808 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  909): Attempted to unregister already unregistered input channel '422c6808 com.test.thalitest.MainActivity (s)'
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
I/WindowManager(  909): WINDOW DIED Window{422c6808 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4507
D/CaptivePortalTracker(  909): NoActiveNetworkState
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 4559): type=WIFI subType= reason=null isConnected=true
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4559/10154)
D/PMS     (  909): acquireWL(43c14bf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/WifiService(  909): Client connection lost with reason: 4
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4345aad0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
I/ActivityManager(  909): Process com.test.thalitest (pid 4507) has died.
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/PMS     (  909): releaseWL(4345aad0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(43c14bf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
I/ActivityManager(  909): Recipient 4380
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2366/10021)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1349): Unsupported attribute readOnly
W/Binder  ( 1211): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1211): java.lang.NullPointerException
W/Binder  ( 1211): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1211): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1211): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1211): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4507 uid 10389
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1326): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/MobileConnectivityChangeReceiver( 4615): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4615): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1326): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1326): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1326): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/PMS     (  909): acquireWL(43573b38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1450461099328 min interval config: 0 actual interval: 49368
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): releaseWL(43573b38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 13.519MB for 1821008-byte allocation
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2189): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2189): num queued entries: 0
,I/iu.UploadsManager( 2189): num updated entries: 0
,I/iu.SyncManager( 2189): NEXT; no task
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1356): [NET] getaddrinfo-,err=8
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1356): [NET] getaddrinfo-, 1
D/libc    ( 1356): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d658 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(4328cf60): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 239
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1356): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,W/Settings( 4742): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4742/10029)
,D/PMS     (  909): acquireWL(43bb23d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  909): releaseWL(4328cf60): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/PMS     (  909): releaseWL(43bb23d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(425dd000): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/PMS     (  909): releaseWL(425dd000): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1218269164
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2189): [NET] getaddrinfo-, 1
,D/libc    ( 2189): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9922 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2189): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2189): Sending checkin request (12209 bytes)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=3 [26][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
W/fb4a(:<default>):UserScope( 4579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,E/fb4a(:<default>):LocalFbBroadcastManager( 4579): Called registerBroadcastReceiver twice.
,D/PMS     (  909): acquireWL(425e8d80): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4559 10154 null
,W/ContextImpl( 4559): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4559, uid=10154, userID:0
,I/MusicLeanback( 4559): Conditions not met for autocaching.
,I/MusicLeanback( 4559): Stop autocaching.
D/PMS     (  909): releaseWL(425e8d80): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4559): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/PMS     (  909): releaseWL(4361be78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,I/CheckinTask( 2189): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2189): Checking schedule, now: 1450461150017 next: 1450984087012
,I/CheckinService( 2189): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,I/CheckinService( 2189): Checking schedule, now: 1450461150039 next: 1450984087012
,I/CheckinService( 2189): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,D/CheckinService( 2189): Recording last checkin time for package unspecified as 1450461150044
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(41ff96e0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5b0b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4,
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/23.59.123.86,
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!,
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4,
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4649): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1504): service - handleMessage() stop self
,D/AutoSetting( 1504): service - onDestroy() END
,D/AutoSetting( 1504): service - handleMessage() quit looper
,I/ActivityManager(  909): Killing 4325:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4325
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4325
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1326): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1326): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1326): service - requestNLP() NetworkLocationProvider not enabled
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4803 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsUpdated
,W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Scheme: "smsto"
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,E/ExternalAccountType( 1349): Unsupported attribute readOnly
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Scheme: "sms"
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,W/dalvikvm( 4803): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4803): VFY: unable to resolve instance field 36
,W/dalvikvm( 4803): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4803): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4803): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4803): MmsConfig.loadMmsSettings
,I/ActivityManager(  909): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4826 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4803, uid=10111, userID:0
,I/ProviderInstaller( 4803): Installed default security provider GmsCore_OpenSSL
,W/Settings( 4803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4826): onCreate
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4803, uid=10111, userID:0
,V/GetPrviateResource( 4826): GetPrviateResource
V/GetPrviateResource( 4826): GetPrviateResource
,D/MmsCustomizationProvider( 4826): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4803, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4803, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4803, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4803, uid=10111, userID:0
,D/MmsCustomizationProvider( 4826): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/PMS     (  909): acquireWL(43242020): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4803 10111 null
,I/Babel   ( 4803): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4803): MmsConfig.loadFromDatabase
,I/[PluginManager]RegisterService( 1326): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1326): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,E/Babel   ( 4803): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4803): MmsConfig.loadFromResources
I/ActivityManager(  909): Resuming delayed broadcast
,E/Babel   ( 4803): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4803): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4826): sense_version=6.0
,D/BTAccessoryUtil( 4826): createReceiver
,D/PMS     (  909): releaseWL(43242020): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/Process (  909): killProcessQuiet, pid=3961
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  909): Killing 3961:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/IcingCorporaProvider( 2865): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/BTAccessoryUtil( 4826): registerReceiver return intent = null
D/MessageCustFlag( 4826): sku_id=99
,W/SystemReader( 4826): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,D/Messaging( 4826): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4826): networkCode: 
,D/MessageCustFlag( 4826): sku_id=99
D/MmsConfig( 4826): SIE smsPri: null
,D/MmsConfig( 4826): networkCode: 
,D/Process (  909): killProcessQuiet, pid=4411
D/HtcTelephonyCapability( 4826): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4826): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4826): getRATByHtcTelephonyCapability:1
W/SystemReader( 4826): Cannot find qct_8960_interface, use default value instead
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4411:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4411
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,D/PMS     (  909): acquireWL(43fd9888): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43fd9888): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  909): acquireWL(43fc8e88): PARTIAL_WAKE_LOCK  AsyncService 0x1 4167 10160 null
,D/PMS     (  909): acquireWL(43fc7558): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
D/PMS     (  909): releaseWL(43fc8e88): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4167): Grow heap (frag case) to 16.949MB for 1821008-byte allocation
,D/PMS     (  909): releaseWL(43fc7558): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Recipient 3961
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  909): acquireWL(43c46580): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43c46580): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(43c078b0): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  909): releaseWL(43c078b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver,
,D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2189): Null package name or gms related package.  Ignoreing.
D/PMS     (  909): acquireWL(43b21538): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2189): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  909): Unable to load service info ResolveInfo{42604110 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/IcingCorporaProvider( 2865): UpdateCorporaTask done [took 601 ms] updated apps [took 601 ms] 
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(42025cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42025cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(425c1710): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(425c1710): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  909): applying state to connected service
,D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): acquireWL(4366bed8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(426081b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(426081b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4366bed8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 -
,D/PhoneApp( 1247): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1247): -- N1 =0
,D/PhoneApp( 1247): -- N2 =0
,D/PhoneApp( 1247): -- N3 =0
,I/Icing   ( 2189): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2189): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  909): releaseWL(43b21538): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4826): mNeedToUpdateDate2 start
,D/MmsConfig( 4826): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4826): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4826): 
D/MmsAsyncWorkHandler( 4826): HM tk = 20001
,D/ReportIndicatorCache( 4826): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4826): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a724e8
,I/Messaging( 4826): mccmnc> 
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1247):  phoneType = -1
,D/MmsSmsV2Provider( 1247): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4826): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4826): [DraftCache/1] refresh
,D/MmsConfig( 4826): networkCode: 
,D/Messaging( 4826): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1247):  phoneType = -1
,D/MmsSmsV2Provider( 1247): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PhoneStorageUtil( 4826): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4826): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4826): createReceiver
,D/MessageCustFlag( 4826): sense_version=6.0
,D/Jerry   ( 4826): start to preload cursor >>>>>>>
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
D/MmsSmsV2Provider( 1247):  phoneType = -1
,D/MmsSmsV2Provider( 1247): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1247): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,V/MmsProvider( 1247): Update uri=content://mms, match=0
,V/MmsProvider( 1247): selection=st=129 AND m_type!=134
,D/Messaging( 4826): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4826): TransactionService is going to be woken up.
D/Messaging( 4826): mNeedToUpdateDate2: false
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/AccFlag ( 1247): sku_id=99
,V/TransactionService( 4826): 1-Creating TransactionService
V/TransactionService( 4826): onStartCommand: 1
,D/MmsSystemEventReceiver( 4826): unRegisterForConnectionStateChanges
V/TransactionService( 4826): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4826): Loading previous transactions.
,D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/DraftCache( 4826): [DraftCache/478] rebuildCache
,D/MmsSmsV2Provider( 1247):  phoneType = -1
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1247): device_type: 1
D/TransactionService( 4826): Force set service start id to 1
V/TransactionService( 4826): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4826): unRegisterForConnectionStateChanges
,D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/TransactionService( 4826): Destroying TransactionService
D/TransactionService( 4826): stopSelfResult: true, mLastHandledServiceId: 1
D/MmsSmsV2Provider( 1247):  phoneType = -1
,D/MmsSmsV2Provider( 1247): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,V/TransactionService( 4826): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
D/Messaging( 4826): ViewCache CreatePreload
,D/Messaging( 4826): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Jerry   ( 1247): URI_DRAFT
,D/Messaging( 4826): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/DraftCache( 4826): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4826): [DraftCache/478] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4826): 
D/MmsAsyncWorkHandler( 4826): HM tk = 20002
,D/Cust_MMSMS( 4826): _has_set_default_values_2=true
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1247): sku_id=99
,D/MsgPreferenceUtils( 4826): def_index: 0
,D/MsgPreferenceUtils( 4826): globalIndex = 1
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/AccFlag ( 1247): sku_id=99
D/MsgPreferenceUtils( 4826): phone state: true
D/MsgPreferenceUtils( 4826): sd state: false
,D/MsgPreferenceUtils( 4826): vIndex = 0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{434505d0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  909): acquireWL(43a8a2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{432231a0: PendingIntentRecord{4268b398 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122381, Int=0
,D/PMS     (  909): releaseWL(43a8a2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(432abd30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [12][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/GAV4    ( 4803): Thread[GAThread,5,main]: No campaign data found.
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(43662c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43662c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(432abd30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(425f2190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(425f2190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42589820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(4261dad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4292dda0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1226): Vacuum at: now=1450461163462 tag=VacuumService
D/PMS     (  909): releaseWL(42589820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4261dad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(437a2520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4292dda0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(437a2520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42ad95c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(42ad95c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(425e8268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(425e8268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(434e28d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(434e28d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(42bdbe38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(43777868): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43777868): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43fad118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42bdbe38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4261a958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(4261a958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1226): Scheduling Phenotype for one-off execution 4037 seconds from now (1450461163996)
,D/GetConfigurationSnapshotOperation( 1226): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1226): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1226): Using platform SSLCertificateSocketFactory
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 1226): [NET] getaddrinfo-, 1
D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5598 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(43fad118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43616d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(43616d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  909): acquireWL(43137378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(43137378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(428e4180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428e4180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(437859e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{4259d490: PendingIntentRecord{4249fc48 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135904, Int=0
,D/PMS     (  909): releaseWL(437859e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/AutoSetting( 1326): service - has update message, not stop
,D/AutoSetting( 1326): service - mHandler: update timezone
,D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1504): service - onCreate()
,D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1504): service - mHandler: update timezone
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1504): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1504): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1504): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1504): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41ac8978 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 8 2 11
,D/PMS     (  909): acquireWL(42552488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42552488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(428e2358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422c6a78: PendingIntentRecord{423153d8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141877, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(4401deb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(428e2358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =bc91 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
,D/PMS     (  909): releaseWL(4401deb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{4401d4a8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): acquireWL(4387c388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(4387c388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1326): service - handleMessage() stop self
,D/AutoSetting( 1326): service - onDestroy() END
,D/AutoSetting( 1326): service - handleMessage() quit looper
,I/ActivityManager(  909): Killing 4433:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4433
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1504): service - handleMessage() stop self
,D/AutoSetting( 1504): service - onDestroy() END
,D/AutoSetting( 1504): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4447
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4447:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4447
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4433
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(436c89d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10027}
,V/AlarmManager(  909): sending alarm PendingIntent{43b46500: PendingIntentRecord{43704da0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173387, Int=0
,D/PMS     (  909): releaseWL(436c89d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(43644eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43644eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(4357c320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4357c320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(425db0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PMS     (  909): releaseWL(425db0e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(436106f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436106f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(4378ff18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4378ff18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(4422d3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(4422d3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(434d8160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434d8160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4358f8c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=319140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4358f8c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  909): killProcessQuiet, pid=4077
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4077:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4077
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43b28948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43b28948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  909): << updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(4328d278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4328d278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(435f4778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(435f4778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43bbb260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43bbb260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42735508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=439140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42735508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43611d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43611d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43a84e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a84e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(42a65618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=499139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42a65618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Disconnect event
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1185): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8eebbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1185): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: Ext,ernal notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  909): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  909):    returned true
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  909): [RunningState] Stop DHCP
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
,D/Tethering(  909): interfaceStatusChanged wlan0, false
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20385 mDataStallAlarmIntent=null
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  909): acquireWL(435a7910): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  909): isAvailable+-
D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  909): doBoolean: SET pno 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1185): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,V/NativeCrypto( 1356): Read error: ssl=0x63f3acd8: I/O error during system call, Connection timed out
D/libc    (  365): [NET] entry_id:1   entry:0xb7783410  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb7783830  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb7783108  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb7782fd8  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb77832b8  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x63f3acd8: I/O error during system call, Broken pipe
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/PMS     (  909): acquireWL(43bf0890): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  909): acquireWL(4361baa8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I//system/bin/ip(  365): RTNETLINK answers: No such process
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  909): doBoolean: SET pno 0
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1185): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1356/10029)
,D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1185): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1185): Failed to initiate AP scan
I/wpa_supplicant( 1185): Failed to initiate AP scan, Failed_to_scan_counter:1
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiNative-wlan0(  909):    returned true
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/PMS     (  909): releaseWL(43bf0890): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
,D/PMS     (  909): releaseWL(4361baa8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(43a98fd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,D/PMS     (  909): releaseWL(43a98fd8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1185): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1185): Failed to initiate AP scan
I/wpa_supplicant( 1185): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
,D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4559/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
V/Tethering(  909): bSetPropertyMultiRAB:false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4559): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2366/10021)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/AutoSetting( 1326): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4615): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4615): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1326): Util - no network available!
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
,D/AutoSetting( 1326): service - onCreate()
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
,D/AutoSetting( 1326): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  909): request 42389730 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1326): service - mHandler: cancel location update
,D/AutoSetting( 1326): service -           changes count: 0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/iu.Environment( 2189): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
I/iu.UploadsManager( 2189): num queued entries: 0
I/iu.UploadsManager( 2189): num updated entries: 0
,I/iu.SyncManager( 2189): NEXT; no task
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1185): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1185): Failed to initiate AP scan
,I/wpa_supplicant( 1185): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1185): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1185): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=12 entropy=0
D/wpa_supplicant( 1185): Add randomness: count=13 entropy=1
D/wpa_supplicant( 1185): Add randomness: count=14 entropy=2
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1185): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1185): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1185): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1185): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1185): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=15 entropy=3
D/wpa_supplicant( 1185): Add randomness: count=16 entropy=4
D/wpa_supplicant( 1185): Add randomness: count=17 entropy=5
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1185): WPS:, AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1185): State: DISCONNECTED -> INACTIVE
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiNative-wlan0(  909): doBoolean: SET pno 1
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =INACTIVE,
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43626da0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43626da0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43626da0 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1185): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (489) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-62
I/wpa_supplicant( 1185): tsf=0000000104791105
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000104791089
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=5
I/wpa_supplicant( 1185): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-62
I/wpa_supplicant( 1185): tsf=0000000505912363
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1185): ssid=01ABC
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=6
I/wpa_supplicant( 1185): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1185): freq=2427
I/wpa_supplicant( 1185): level=-79
I/wpa_supplicant( 1185): tsf=0000000505912374
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=Gonzos
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 104791105, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 104791089, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -62, frequency: 2412, timestamp: 505912363, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 505912374, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
D/wpa_supplicant( 1185): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1185): Add randomness: count=18 entropy=6
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0,
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
,D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
,D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
,D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1185): reply (489) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-62
I/wpa_supplicant( 1185): tsf=0000000507893667
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000104791089
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=5
I/wpa_supplicant( 1185): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-62
I/wpa_supplicant( 1185): tsf=0000000505912363
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1185): ssid=01ABC
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=6
I/wpa_supplicant( 1185): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1185): freq=2427
I/wpa_supplicant( 1185): level=-79
I/wpa_supplicant( 1185): tsf=0000000505912374
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=Gonzos
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 507893667, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 104791089, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -62, frequency: 2412, timestamp: 505912363, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (4) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 505912374, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 4 to mScanResults
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1185): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1185): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1185): Failed to initiate AP scan
,I/wpa_supplicant( 1185): Failed to initiate AP scan, Failed_to_scan_counter:4
,D/WifiNative-wlan0(  909):    returned true
D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1185): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiStateMachine(  909): Enter handleAssociateRejectEvent
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  909): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
,D/WifiStateMachine(  909): Exit handleAssociateRejectEvent
,I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
D/wpa_supplicant( 1185): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=19 entropy=7
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1185): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
D/wpa_supplicant( 1185): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=20 entropy=8
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1185): State: INACTIVE -> INACTIVE
,D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1',
D/WifiP2pService(  909): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 75,
D/wpa_supplicant( 1185): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1185): reply (238) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-62
I/wpa_supplicant( 1185): tsf=0000000507893667
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000512093140
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (2) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 507893667, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 512093140, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 2 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
D/WifiNative-wlan0(  909): doBoolean: SET pno 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1185): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1185): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1185): Failed to initiate AP scan
,I/wpa_supplicant( 1185): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
D/WifiNative-wlan0(  909):    returned true
,I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1185): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1185): Failed to initiate AP scan
,I/wpa_supplicant( 1185): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1185): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1185): Failed to initiate AP scan
,I/wpa_supplicant( 1185): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=21 entropy=9
D/wpa_supplicant( 1185): Add randomness: count=22 entropy=10
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-61
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1185): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  909):    returned false
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1185): reply (238) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-61
I/wpa_supplicant( 1185): tsf=0000000518134545
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000518134519
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 518134545, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 518134519, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 2 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1226): getScanResults enter 
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (2) end of scan result ==
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{422f9b70 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1185): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
,D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  909): Enter handleAssociateRejectEvent
D/WifiStateMachine(  909): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/WifiStateMachine(  909): Exit handleAssociateRejectEvent
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
,I/wpa_supplicant( 1185): wpa_supplicant_scan enter
,I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=23 entropy=11
D/wpa_supplicant( 1185): Add randomness: count=24 entropy=12
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1185):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-61
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate, with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 118,5): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (238) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-61
I/wpa_supplicant( 1185): tsf=0000000522695247
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000522695221
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 522695247, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  909): == (2) end of scan result ==
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (2) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 522695221, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 2 to mScanResults
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WirelessDisplayService(  909): HANDLE_WIFI_DIS,
D/WirelessDisplayService(  909): HANDLE_STOP_DIS,
D/WirelessDisplayService(  909): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  909): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1,
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/wpa_supplicant( 1185): nl80211: Event message available,
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
,I/wpa_supplicant( 1185): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
,D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED,
D/WifiStateMachine(  909): Enter handleAssociateRejectEvent
D/WifiStateMachine(  909): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
,D/WifiStateMachine(  909): Exit handleAssociateRejectEvent,
,I/wpa_supplicant( 1185): wpa_supplicant_scan enter,
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/PMS     (  909): acquireWL(43fe7cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43fe7cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+,
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=25 entropy=13
D/wpa_supplicant( 1185): Add randomness: count=26 entropy=14
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1185):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-61
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate, with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (238) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-61
I/wpa_supplicant( 1185): tsf=0000000527274784
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000527274759
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ####
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 527274784, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 527274759, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 2 to mScanResults
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  909): == (2) end of scan result ==
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/wpa_supplicant( 1185): nl80211: Event message available,
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
,I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1185): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
,D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiStateMachine(  909): Enter handleAssociateRejectEvent
D/WifiStateMachine(  909): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
,D/WifiStateMachine(  909): Exit handleAssociateRejectEvent,
,I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1185): nl80211: Event message available
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=27 entropy=15
D/wpa_supplicant( 1185): Add randomness: count=28 entropy=16
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1185):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-61
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate, with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 118,5): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (238) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-61
I/wpa_supplicant( 1185): tsf=0000000532364311
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000532364284
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 532364311, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 532364284, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 2 to mScanResults
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1185): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
,D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  909): WifiMonitor:getStatusCodeFromEventString() 1
D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
,D/HTCRequest(  909): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiStateMachine(  909): Enter handleAssociateRejectEvent
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  909): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
,D/WifiStateMachine(  909): Exit handleAssociateRejectEvent
,D/AutoSetting( 1326): service - handleMessage() stop self
,D/AutoSetting( 1326): service - handleMessage() quit looper
,D/AutoSetting( 1326): service - onDestroy() END
,I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=29 entropy=17
D/wpa_supplicant( 1185): Add randomness: count=30 entropy=18
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1185):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-61
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate, with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantSt,ateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (238) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-61
I/wpa_supplicant( 1185): tsf=0000000537264455
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000000537264430
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ####
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 537264455, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 537264430, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 2 to mScanResults
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
,D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event,
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1185): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Add randomness: count=31 entropy=19
I/wpa_supplicant( 1185): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): TDLS: Remove peers on association
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1185): EAPOL: enable timer tick
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1185): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): Get randomness: len=32 entropy=20
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiStateMachine(  909): Associated
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8eec9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  909): updateConnectedAP...,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6edcb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    broadcast key
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1185): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1185): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1185): set send_ind_to_ndc = 0
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1185): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 1185): EAPOL authentication completed successfully
I/wpa_supplicant( 1185): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
,D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...,
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  909):    returned true
,D/DhcpStateMachine(  909): [StoppedState] Start DHCP
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(4291ded8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
,D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
D/wpa_supplicant( 1185): nl80211: Event message available
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1185): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1185): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 1
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  909):    returned null
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42491200 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42491200 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1185): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1185): EAPOL: disable timer tick
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
D/WifiP2pService(  909): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(4291ded8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): gateway: /192.168.1.1
D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  909): WAN detection
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
,D/WISPrService( 3846): >>>>>WISPrService start isConnected = true<<<<<
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1185): Change stage from stage0 to stage3
D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@423f1f80
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
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
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/PMS     (  909): acquireWL(441240d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/PMS     (  909): acquireWL(44082930): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,D/PMS     (  909): acquireWL(4405fd28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(44082930): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1450461150044 min interval config: 0 actual interval: 430526
,I/CheckinService( 2189): Checking schedule, now: 1450461580578 next: 1450461180012
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,I/CheckinService( 2189): active receiver: enabled
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(441240d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2189, uid=10029, userID:0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2189): Preparing to send checkin request
,I/EventLogService( 2189): Accumulating logs since 1450461147624
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=392338492
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  909): releaseWL(435a7910): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4742/10029)
W/Settings( 4742): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  909): bSetPropertyMultiRAB:false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/PMS     (  909): acquireWL(423ad918): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  909): Found interface wlan0
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4559/10154)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(424ca110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 4559): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/PMS     (  909): releaseWL(424ca110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/PMS     (  909): releaseWL(423ad918): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2366/10021)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1326): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4615): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4615): onReceive CONNECTIVITY_CHANGE networkType=1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
,D/AutoSetting( 1326): service - onCreate()
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
D/AutoSetting( 1326): service - AddressCache: using context: com.htc.Weather
D/WVCdm   (  372): PrepareKeyRequest: nonce=761407578
D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1326): service - onStartCommand() screen is off, don't request location
D/LocationManagerService(  909): request 42389730 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1326): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1326): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(42317828): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1450461150044 min interval config: 0 actual interval: 431599
D/PMS     (  909): releaseWL(42317828): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2189): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2189): num queued entries: 0
,I/iu.UploadsManager( 2189): num updated entries: 0
,I/iu.SyncManager( 2189): NEXT; no task
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
D/libc    ( 1356): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1356): [NET] getaddrinfo-, 1
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/libc    ( 1356): [NET] getaddrinfo_proxy+
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4d23 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  909): acquireWL(42608858): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 279
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1356): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2189): [NET] getaddrinfo-, 1
D/libc    ( 2189): [NET] getaddrinfo_proxy+
V/NativeCrypto( 2189): SSL shutdown failed: ssl=0x6e2b6c00: I/O error during system call, Connection timed out
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
V/NativeCrypto( 2189): SSL shutdown failed: ssl=0x665cd210: I/O error during system call, Connection timed out
D/libc    (  365): [NET] +++++ res_nsend xid =bc53 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2189): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2189): Sending checkin request (12206 bytes)
,D/PMS     (  909): acquireWL(42444c38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  909): releaseWL(42608858): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/PMS     (  909): releaseWL(42444c38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(437e7498): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(437e7498): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=25 [28][7][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e187 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/23.59.123.86
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [4][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,I/CheckinTask( 2189): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2189): Checking schedule, now: 1450461583598 next: 1450984520592
,I/CheckinService( 2189): active receiver: disabled
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
I/CheckinService( 2189): Checking schedule, now: 1450461583628 next: 1450984520592
,I/CheckinService( 2189): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,D/CheckinService( 2189): Recording last checkin time for package unspecified as 1450461583635
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(4405fd28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): acquireWL(43a5d100): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4803 10111 null
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1326): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1326): handle notify Blinkfeed plugin client changed
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
,W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/dalvikvm-heap( 1275): Grow heap (frag case) to 12.645MB for 53840-byte allocation
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/ActivityManager(  909): Resuming delayed broadcast
W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsUpdated
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PMS     (  909): releaseWL(43a5d100): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
,I/IcingCorporaProvider( 2865): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PMS     (  909): acquireWL(425de2b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4167 10160 null
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,E/ExternalAccountType( 1349): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
D/PMS     (  909): acquireWL(437da038): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(425de2b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PMS     (  909): releaseWL(437da038): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  909): acquireWL(43678bd0): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43678bd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(42fd33c0): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  909): releaseWL(42fd33c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(430a53e0): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  909): releaseWL(430a53e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(43c0f4b0): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2189): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2189): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2865): UpdateCorporaTask done [took 1123 ms] updated apps [took 1123 ms] 
I/ActivityManager(  909): Resuming delayed broadcast
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,W/PackageManager(  909): Unable to load service info ResolveInfo{43b36358 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 -
,I/Icing   ( 2189): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): acquireWL(43319020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(43319020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): acquireWL(44056c78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(44056c78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43654ae0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43654ae0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2189): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  909): releaseWL(43c0f4b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43768560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43768560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PhoneApp( 1247): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1247): -- N1 =0
,D/PhoneApp( 1247): -- N2 =0
,D/PhoneApp( 1247): -- N3 =0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{43780810 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  909): acquireWL(4387c128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=559140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4387c128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1326): service - handleMessage() stop self
,D/AutoSetting( 1326): service - mHandler: update timezone
,D/AutoSetting( 1326): service - handleMessage() quit looper
,D/AutoSetting( 1326): service - onDestroy() END
,D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1504): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1504): service - mHandler: update timezone
,D/AutoSetting( 1504): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1504): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1504): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1504): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41b13350 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 3 7 2 11
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{437db458 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): acquireWL(42ea5718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42ea5718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1504): service - handleMessage() stop self
,D/AutoSetting( 1504): service - onDestroy() END
,D/AutoSetting( 1504): service - handleMessage() quit looper
,D/PMS     (  909): acquireWL(430e12c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(430e12c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(43242278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=619140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43242278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1247): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1247): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1247): sku_id=99
D/ContactMessageStore( 1247): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1247): start background delete task...
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
,D/PMS     (  909): acquireWL(43331540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43331540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(428e0808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=679140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428e0808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42626e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42626e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(432c2828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(432c2828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43610840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=739139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1275): Grow heap (frag case) to 12.703MB for 50416-byte allocation
,D/PMS     (  909): releaseWL(43610840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43a92e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a92e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43694670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43694670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43753ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=799140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43753ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(437279a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(437279a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(430ba088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(430ba088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43250d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=859140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43250d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(436e5dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436e5dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43bdceb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  909): releaseWL(43bdceb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43099340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=919140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43099340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
D/PMS     (  909): acquireWL(425f7288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41cc8748: PendingIntentRecord{423fc738 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782566, Int=0
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5026 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{41b30288: PendingIntentRecord{41af77c8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450461253814, Int=10800000
,V/AlarmManager(  909): sending alarm PendingIntent{43ac3768: PendingIntentRecord{426737d8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450461631240, Int=1800000
,V/AlarmManager(  909): sending alarm PendingIntent{424d4810: PendingIntentRecord{424ceab8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450461974231, Int=900000
,D/PMS     (  909): acquireWL(43a57748): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4354c698): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): releaseWL(425f7288): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): releaseWL(43a57748): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PowerUsageService( 4701): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4701): MY_DEBUG = false
,I/EventLogService( 2189): Aggregate from 1450461580603 (log), 1450459831200 (data)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (5026/10049)
,W/BatSI   (  909): Couldn't get kernel wake lock stats,
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(4354c698): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=4483
,I/ActivityManager(  909): Killing 4483:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4483
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(42826658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/BatteryService(  909): n_update end
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42826658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(423d0358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423d0358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(431c3d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(431c3d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4377da38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/SmartSyncUtils( 4701): isEpsOn(), nState = 0
V/AlarmManager(  909): sending alarm PendingIntent{41cd3ca8: PendingIntentRecord{423a47b8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450462047588, Int=0
D/PMS     (  909): releaseWL(4377da38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  909): acquireWL(43c70eb8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4701 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4701): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4701): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4701): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4701): SettingOnTime = 1450504800000, randomSettingOnTime = 1450504492000
,D/SmartSyncScreenOnOffTimeReceiver( 4701): SettingOffTime = 1450490400000, randomSettingOffTime = 1450496772000
,D/SmartSyncScreenOnOffTimeReceiver( 4701): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4701): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4701): bNightModeTurnOffOnce = false
,D/PMS     (  909): releaseWL(43c70eb8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  909): acquireWL(43523760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43523760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42489f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(42489f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42545f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42545f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(425f79d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(425f79d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43798c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43798c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4321b958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1099140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4321b958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42688618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42688618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(423c5d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423c5d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(431cfa88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1159140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(431cfa88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Disconnect event
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,I/wpa_supplicant( 1185): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1185): TDLS: Remove peers on disassociation
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 0
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8eebbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1185): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185),: EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  909): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/WifiP2pService(  909): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  909): [RunningState] Stop DHCP
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20386 mDataStallAlarmIntent=null
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMS     (  909): acquireWL(435b16c8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  909): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
D/UsbnetStateTracker(  909): isAvailable+-
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1185): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState,
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '74 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 74 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '75 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 75 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '76 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 76 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
,D/ConnectivityService(  909): resetConnections(wlan0, 3)
,V/NativeCrypto( 1356): Read error: ssl=0x66285a00: I/O error during system call, Connection timed out
D/libc    (  365): [NET] entry_id:1   entry:0xb7783410  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb7783108  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb7782fd8  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x66285a00: I/O error during system call, Broken pipe
D/PMS     (  909): acquireWL(4266f038): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  909): acquireWL(4369bf50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1185): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1185): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
,D/PMS     (  909): releaseWL(4266f038): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiNative-wlan0(  909):    returned false
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore,
,D/PMS     (  909): releaseWL(4369bf50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 4559): type=WIFI subType= reason=null isConnected=false
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4559/10154)
D/PMS     (  909): acquireWL(43fc86c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/PMS     (  909): releaseWL(43fc86c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2366/10021)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/AutoSetting( 1326): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4615): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4615): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
,D/AutoSetting( 1326): Util - no network available!
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
,D/AutoSetting( 1326): service - onCreate()
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
,D/AutoSetting( 1326): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  909): request 42389730 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1326): service - mHandler: cancel location update
,D/AutoSetting( 1326): service -           changes count: 0
,I/iu.Environment( 2189): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2189): num queued entries: 0
,I/iu.UploadsManager( 2189): num updated entries: 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/iu.SyncManager( 2189): NEXT; no task
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=32 entropy=0
D/wpa_supplicant( 1185): Add randomness: count=33 entropy=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1185):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-61
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allo,wed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1185): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  909):    returned false
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1185): reply (238) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-61
I/wpa_supplicant( 1185): tsf=0000001188162491
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=7
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000001188162465
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ####
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 1188162491, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1188162465, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): add 2 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4394cc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4394cc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+,
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-,
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1185): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Add randomness: count=34 entropy=2
I/wpa_supplicant( 1185): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): TDLS: Remove peers on association
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1185): EAPOL: enable timer tick
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1185): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): Get randomness: len=32 entropy=3
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
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiStateMachine(  909): Associated
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
,D/Tethering(  909): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
,D/Tethering(  909): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...,
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8eec9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6edcb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    broadcast key
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1185): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1185): State: GROUP_HANDSHAKE -> COMPLETED
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1185): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=6
,I/wpa_supplicant( 1185): set send_ind_to_ndc = 0
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1185): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1185): EAPOL authentication completed successfully
I/wpa_supplicant( 1185): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...,
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  909):    returned true
,D/DhcpStateMachine(  909): [StoppedState] Start DHCP
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 1
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1185): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(425f6658): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  909):    returned null
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42491200 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42491200 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 1185): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1185): EAPOL: disable timer tick
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ProcessCpuTracker(  909): Skipping unknown process pid 5086
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  909): releaseWL(425f6658): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  909): gateway: /192.168.1.1
D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/NativeDaemonConnector.ResponseQueue(  909): more buffered than allowed: 10 >= 10
,E/NativeDaemonConnector.ResponseQueue(  909): Removing request: null (6)
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
,D/WifiWatchdogStateMachine(  909): WAN detection
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/WISPrService( 3846): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1185): Change stage from stage0 to stage3
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@423f1f80
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
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
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
E/NativeDaemonConnector.ResponseQueue(  909): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  909): Removing request: null (14)
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  909): acquireWL(434f07a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(425def40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(434f07a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(438192c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(425def40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1450461583635 min interval config: 0 actual interval: 648517
I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2189): Checking schedule, now: 1450462232163 next: 1450461613592
,I/CheckinService( 2189): active receiver: enabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2189, uid=10029, userID:0
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/CheckinService( 2189): Preparing to send checkin request
,I/EventLogService( 2189): Accumulating logs since 1450461974336
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2628033232
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4742/10029)
W/Settings( 4742): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/PMS     (  909): releaseWL(435b16c8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,D/WVCdm   (  372): PrepareKeyRequest: nonce=60711141
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  909): NoActiveNetworkState
,V/Tethering(  909): bSetPropertyMultiRAB:false
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4559/10154)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/NetworkMonitor( 4559): type=WIFI subType= reason=null isConnected=true
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  909): Found interface wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
I/WVCdm   (  372): CdmEngine::CloseSession
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/PMS     (  909): acquireWL(436c3608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/PMS     (  909): acquireWL(430ae620): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/PMS     (  909): releaseWL(430ae620): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(436c3608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2366/10021)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/CheckinRequestBuilder( 2189): Classify the device as Phone.
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1326): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/MobileConnectivityChangeReceiver( 4615): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4615): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1326): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1326): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1326): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2189): [NET] getaddrinfo-,err=8
V/NativeCrypto( 2189): SSL shutdown failed: ssl=0x6e2b6c00: I/O error during system call, Connection timed out
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2189): [NET] getaddrinfo-, 1
D/libc    ( 2189): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1577 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/PMS     (  909): acquireWL(44057528): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1450461583635 min interval config: 0 actual interval: 649609
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [2][0][0]
D/PMS     (  909): releaseWL(44057528): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
I/iu.Environment( 2189): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2189): num queued entries: 0
,I/iu.UploadsManager( 2189): num updated entries: 0
,I/iu.SyncManager( 2189): NEXT; no task
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  909): acquireWL(4268d368): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1356): [NET] getaddrinfo-,err=8
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1356): [NET] getaddrinfo-, 1
D/libc    ( 1356): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =87d8 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 119
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2189): [NET] getaddrinfo_proxy-, success
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1356): [NET] getaddrinfo_proxy-, success
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2189): Sending checkin request (12213 bytes)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  909): acquireWL(433093b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  909): releaseWL(4268d368): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/PMS     (  909): releaseWL(433093b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43632078): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(43632078): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=30 [26][8][0]
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,I/CheckinTask( 2189): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2189): Checking schedule, now: 1450462234119 next: 1450985171113
,I/CheckinService( 2189): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,I/CheckinService( 2189): Checking schedule, now: 1450462234140 next: 1450985171113
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,I/CheckinService( 2189): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,D/CheckinService( 2189): Recording last checkin time for package unspecified as 1450462234152
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(438192c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ae8e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/23.59.123.86
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/PMS     (  909): acquireWL(4405b1f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4803 10111 null
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
,I/dalvikvm-heap( 1275): Grow heap (frag case) to 12.694MB for 53840-byte allocation
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/[PluginManager]RegisterService( 1326): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1326): handle notify Blinkfeed plugin client changed
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
D/PMS     (  909): releaseWL(4405b1f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/ActivityManager(  909): Resuming delayed broadcast
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsUpdated
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/IcingCorporaProvider( 2865): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  909): acquireWL(425b49b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4167 10160 null
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PMS     (  909): releaseWL(425b49b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Scheme: "mmsto"
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  909): acquireWL(42402b68): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,E/ExternalAccountType( 1349): Unsupported attribute readOnly
,D/PMS     (  909): releaseWL(42402b68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(425b5690): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  909): releaseWL(425b5690): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  909): acquireWL(436a8330): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(436a8330): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(42602190): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2189): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  909): Waited long enough for: ServiceRecord{4363cbc0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/Icing   ( 2189): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2865): UpdateCorporaTask done [took 854 ms] updated apps [took 854 ms] 
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,W/PackageManager(  909): Unable to load service info ResolveInfo{4264d8f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Icing   ( 2189): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2189): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  909): releaseWL(42602190): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1247): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1247): -- N1 =0
,D/PhoneApp( 1247): -- N2 =0
,D/PhoneApp( 1247): -- N3 =0
,E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 -
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): acquireWL(4361fee8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): releaseWL(4361fee8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(43fd9a28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(43fd9a28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(431cf0b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(431cf0b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43634f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43634f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(432d5108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1219139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(432d5108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1326): service - mHandler: update timezone
,D/AutoSetting( 1326): service - handleMessage() stop self
,D/AutoSetting( 1326): service - handleMessage() quit looper
,D/AutoSetting( 1326): service - onDestroy() END
,D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1504): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1504): service - mHandler: update timezone
,D/AutoSetting( 1504): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1504): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1504): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1504): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41ac8978 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 4 7 2 11
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{4313f2b8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): acquireWL(424740f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(424740f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
V/NotificationService(  909): batLight: plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c80000
D/qdlights(  909): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/HeadsetPhoneState( 1604): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,D/DotMatrix( 1566): [EventService] reorderNotification, total:1
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/PowerUI ( 1118): closing low battery warning: level=98
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3846): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3846): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3846): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3846): Cust_ConnectToPC   : spcsc>false
D/        ( 3846): Cust_ConnectToPC   : IPT>true
,D/        ( 3846): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3846): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3846): Index of the first 1 = -1
W/ContextImpl( 3846): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3846): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3846): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3846): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3846): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3846): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1118): status:2 level:98 unsupport:false plugged:true
,D/AutoSetting( 1504): service - handleMessage() stop self
,D/AutoSetting( 1504): service - onDestroy() END
,D/AutoSetting( 1504): service - handleMessage() quit looper
,D/PMS     (  909): acquireWL(43530810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43530810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=98
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43fc4b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1279140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43fc4b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4367a018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(4367a018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=98
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(428e2dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428e2dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43672360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1339139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43672360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(435a7418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(435a7418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(426846d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1399139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(426846d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42679b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42679b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43c5bb38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1459140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c5bb38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43133cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43133cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=99
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43a91290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a91290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4310b588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1519140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4310b588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43c5b880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c5b880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/PowerUI ( 1118): closing low battery warning: level=99
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1118): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43718248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43718248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=99
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43c11b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1579139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c11b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4404ca98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4404ca98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=99
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4387b960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1639139, Int=0
,D/PMS     (  909): releaseWL(4387b960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Disconnect event
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1185): TDLS: Remove peers on disassociation
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8eebbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1185): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplic,ant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/WifiNative-wlan0(  909):    returned true
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/PMS     (  909): acquireWL(435f97f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{41cc8748: PendingIntentRecord{423fc738 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1653395, Int=0
D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20387 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
D/PMS     (  909): releaseWL(435f97f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMS     (  909): acquireWL(44029ec8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  909):    returned true
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): Done.
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): Setting timer for 720seconds
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
E/NativeDaemonConnector.ResponseQueue(  909): more buffered than allowed: 11 >= 10
E/NativeDaemonConnector.ResponseQueue(  909): Removing request: null (27)
E/NativeDaemonConnector.ResponseQueue(  909): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  909): Removing request: null (29)
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '95 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 95 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '96 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 96 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1185): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '97 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 97 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
,D/ConnectivityService(  909): resetConnections(wlan0, 3)
V/NativeCrypto( 1356): Read error: ssl=0x66285a00: I/O error during system call, Connection timed out
,D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] entry_id:2   entry:0xb777e8f0  removed 
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  365): [NET] entry_id:1   entry:0xb7787f68  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb7783548  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x66285a00: I/O error during system call, Broken pipe
D/PMS     (  909): acquireWL(42678508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
D/PMS     (  909): acquireWL(4250c228): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1185): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1185): nl80211: Event message available
,D/wpa_supplicant( 1185): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  909):    returned true
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/PMS     (  909): releaseWL(42678508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1185): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  909):    returned false
I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  909): releaseWL(4250c228): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
V/Tethering(  909): bSetPropertyMultiRAB:false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  909): ipv4Default null
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,I/Tethering(  909): No IPv4 upstream interface, giving up.
D/PMS     (  909): acquireWL(432f3340): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(432f3340): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
D/CaptivePortalTracker(  909): NoActiveNetworkState
,I/NetworkMonitor( 4559): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4559/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2366/10021)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/AutoSetting( 1326): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4615): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4615): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
,D/AutoSetting( 1326): Util - no network available!
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
D/AutoSetting( 1326): service - onCreate()
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/AutoSetting( 1326): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/LocationManagerService(  909): request 42389730 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1326): service - mHandler: cancel location update
,D/AutoSetting( 1326): service -           changes count: 0
,I/iu.Environment( 2189): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
I/iu.UploadsManager( 2189): num queued entries: 0
,I/iu.UploadsManager( 2189): num updated entries: 0
,I/iu.SyncManager( 2189): NEXT; no task
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=35 entropy=0
D/wpa_supplicant( 1185): Add randomness: count=36 entropy=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1185): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=37 entropy=2
D/wpa_supplicant( 1185): Add randomness: count=38 entropy=3
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1185): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 75
,D/wpa_supplicant( 1185): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1185): reply (258) for get BSS: id=8
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000001663860241
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=9
I/wpa_supplicant( 1185): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1185): freq=2427
I/wpa_supplicant( 1185): level=-79
I/wpa_supplicant( 1185): tsf=0000001663860267
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=Gonzos
I/wpa_supplicant( 1185): ####
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1663860241, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (2) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 1663860267, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 2 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
D/wpa_supplicant( 1185): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1185): Add randomness: count=39 entropy=4
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 10
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8eed4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
,I/wpa_supplicant( 1185): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb8eed4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb8eec718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8eec718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb8eec718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (377) for get BSS: id=8
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000001663860241
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=9
I/wpa_supplicant( 1185): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1185): freq=2427
I/wpa_supplicant( 1185): level=-79
I/wpa_supplicant( 1185): tsf=0000001663860267
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=Gonzos
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=10
,I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-62
I/wpa_supplicant( 1185): tsf=0000001665844269
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ####
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1663860241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 1663860267, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 1665844269, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1185): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Add randomness: count=40 entropy=5
I/wpa_supplicant( 1185): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): TDLS: Remove peers on association
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1185): EAPOL: enable timer tick
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1185): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): Get randomness: len=32 entropy=6
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWit,hEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  909): Associated
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceStatusChanged wlan0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  909): interfaceStatusChanged wlan0, true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8eec9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  909): This record is existed, only update it...
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6edcb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    broadcast key
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1185): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1185): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1185): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1185): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1185): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1185): EAPOL authentication completed successfully
I/wpa_supplicant( 1185): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
,D/Tethering(  909): interfaceStatusChanged wlan0, true
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3846): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WISPrService( 3846): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1185): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  909):    returned true
,D/DhcpStateMachine(  909): [StoppedState] Start DHCP
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 1
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/wpa_supplicant( 1185): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  909):    returned null
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(43785198): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42491200 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42491200 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 1185): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1185): EAPOL: disable timer tick
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  909): acquireWL(43453bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderNotification, total:0
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1604): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/NotificationService(  909): batLight: Full, plugged
D/PMS     (  909): releaseWL(43453bd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
D/HtcPowerSaver(  909): updateBatteryInfo
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  909): << updateStatus
,D/TetherSettings( 3846): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3846): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3846): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3846): Cust_ConnectToPC   : spcsc>false
D/        ( 3846): Cust_ConnectToPC   : IPT>true
D/        ( 3846): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3846): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3846): Index of the first 1 = -1
W/Settings( 3846): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3846): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3846): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3846): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3846): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(43785198): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  909): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): gateway: /192.168.1.1
,D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
,D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  909): doBoolean: SCAN TYPE=ONLY
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/WifiNative-wlan0(  909):    returned true
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
,D/WifiWatchdogStateMachine(  909): WAN detection
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/WISPrService( 3846): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@423f1f80
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1185): Change stage from stage0 to stage3
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
E/NetdConnector(  909): NDC Command {103 resolver setifdns wlan0  192.168.1.1} took too long (805ms)
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/PMS     (  909): acquireWL(43875c78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  909): acquireWL(4374e5a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(44052430): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1450462234152 min interval config: 0 actual interval: 475762
D/PMS     (  909): releaseWL(4374e5a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  365): RTNETLINK answers: No such process
I/CheckinService( 2189): Checking schedule, now: 1450462709922 next: 1450462264113
I/CheckinService( 2189): active receiver: enabled
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2189, uid=10029, userID:0
,I/CheckinService( 2189): Preparing to send checkin request
,I/EventLogService( 2189): Accumulating logs since 1450462232190
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(43875c78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  909): releaseWL(44029ec8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=526582927
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4742): Local Branch: 
I/Adreno-EGL( 4742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4742):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4742): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4742/10029)
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4615/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4559/10154)
I/NetworkMonitor( 4559): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
V/Tethering(  909): bSetPropertyMultiRAB:false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  909): NoActiveNetworkState
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4375fea0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/WVCdm   (  372): CdmEngine::OpenSession
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): acquireWL(43309010): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/PMS     (  909): releaseWL(43309010): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(4375fea0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2366/10021)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/AutoSetting( 1326): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4615): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4615): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1326): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1326): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
D/AutoSetting( 1326): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1326): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1326/10055)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4649/10151)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4167/10160)
,D/PMS     (  909): acquireWL(43657ec0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/WVCdm   (  372): PrepareKeyRequest: nonce=3236570488
,I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1450462234152 min interval config: 0 actual interval: 476841
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43657ec0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2189): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2189): num queued entries: 0
,I/iu.UploadsManager( 2189): num updated entries: 0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
I/iu.SyncManager( 2189): NEXT; no task
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  909): acquireWL(4378de60): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1356): [NET] getaddrinfo-,err=8
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1356): [NET] getaddrinfo-, 1
D/libc    ( 1356): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =347a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1185): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1185): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=41 entropy=0
D/wpa_supplicant( 1185): Add randomness: count=42 entropy=1
D/wpa_supplicant( 1185): Add randomness: count=43 entropy=2
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (377) for get BSS: id=8
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-51
I/wpa_supplicant( 1185): tsf=0000001670221815
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=9
I/wpa_supplicant( 1185): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1185): freq=2427
I/wpa_supplicant( 1185): level=-79
I/wpa_supplicant( 1185): tsf=0000001670221847
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=Gonzos
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=10
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-61
I/wpa_supplicant( 1185): tsf=0000001670221836
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1670221815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 1670221847, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 1670221836, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -61, 0
,V/ScoreHelper(  909): Only print Top 10 in ApScanList
,V/ScoreHelper(  909):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-61], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,D/WifiStateMachine(  909): add 3 to mScanResults
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-51], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
,D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
V/NativeCrypto( 2189): SSL shutdown failed: ssl=0x6e21ca60: I/O error during system call, Connection timed out
D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2189): [NET] getaddrinfo-, 1
D/libc    ( 2189): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =fec5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1356): [NET] getaddrinfo_proxy-, success
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2189): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,I/CheckinTask( 2189): Sending checkin request (12211 bytes)
,D/PMS     (  909): acquireWL(4402b7b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  909): releaseWL(4378de60): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/PMS     (  909): releaseWL(4402b7b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4400d020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(4400d020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=13 [29][4][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,I/CheckinTask( 2189): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2189): Checking schedule, now: 1450462712013 next: 1450985649007
,I/CheckinService( 2189): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4ce7 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,I/CheckinService( 2189): Checking schedule, now: 1450462712052 next: 1450985649007
,I/CheckinService( 2189): active receiver: disabled
,D/CheckinService( 2189): Recording last checkin time for package unspecified as 1450462712058
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024452
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024609
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024682
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024851
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024854
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024857
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027492
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360027504
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360030315
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360031413
,D/PMS     (  909): releaseWL(44052430): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/23.59.123.86
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{44055d48 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/PMS     (  909): acquireWL(43571af8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4803 10111 null
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Scheme: "mms"
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsUpdated
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PMS     (  909): releaseWL(43571af8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/[PluginManager]RegisterService( 1326): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1326): handle notify Blinkfeed plugin client changed
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/IcingCorporaProvider( 2865): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  909): acquireWL(430ae118): PARTIAL_WAKE_LOCK  AsyncService 0x1 4167 10160 null
,D/PMS     (  909): releaseWL(430ae118): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  909): acquireWL(4380bff0): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4380bff0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/ExternalAccountType( 1349): Unsupported attribute readOnly
,D/PMS     (  909): acquireWL(424efcd0): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2189): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  909): Resuming delayed broadcast
,I/Icing   ( 2189): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  909): Unable to load service info ResolveInfo{435d1140 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/IcingCorporaProvider( 2865): UpdateCorporaTask done [took 515 ms] updated apps [took 515 ms] 
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  909): applying state to connected service
,D/PMS     (  909): acquireWL(437920d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(437920d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): acquireWL(42671270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(42671270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4364f280): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4364f280): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Icing   ( 2189): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2189): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
D/PMS     (  909): releaseWL(424efcd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 -
,D/PhoneApp( 1247): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1247): -- N1 =0
,D/PhoneApp( 1247): -- N2 =0
,D/PhoneApp( 1247): -- N3 =0
,D/PMS     (  909): acquireWL(4400dec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4400dec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42675a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1699139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42675a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1326): service - has update message, not stop
,D/AutoSetting( 1326): service - mHandler: update timezone
,D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1504): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1504): service - mHandler: update timezone
,D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1504): service - processTimeZoneID() system nitz: 
D/AutoSetting( 1504): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1504): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1504): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41ac8978 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 3 8 4 11
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{43b19e20 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): acquireWL(4357fad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4357fad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 1326): service - handleMessage() stop self
,D/AutoSetting( 1326): service - handleMessage() quit looper
,D/AutoSetting( 1326): service - onDestroy() END
,D/AutoSetting( 1504): service - handleMessage() stop self
,D/AutoSetting( 1504): service - onDestroy() END
,D/AutoSetting( 1504): service - handleMessage() quit looper
,D/PMS     (  909): acquireWL(437c2850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(437c2850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43134098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1759140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43134098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(4313f170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4313f170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(43aa2900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1819139, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  909): Prepared write state in 47ms
,D/PMS     (  909): releaseWL(43aa2900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  909): Pruning old procstats: /data/system/procstats/state-2015-12-18-03-45-24.bin
,D/PMS     (  909): acquireWL(43a94238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41e6d880: PendingIntentRecord{42548490 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821384, Int=1800000
V/AlarmManager(  909): sending alarm PendingIntent{427842e0: PendingIntentRecord{4288ef10 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1848020, Int=0
D/PMS     (  909): acquireWL(43130df8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
,V/AlarmManager(  909): sending alarm PendingIntent{424d4810: PendingIntentRecord{424ceab8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450462874231, Int=900000
,D/PMS     (  909): releaseWL(43130df8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/LocationManagerService(  909): getAllProviders()=[passive, gps, network]
D/PMS     (  909): releaseWL(43a94238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  909): Couldn't get kernel wake lock stats
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/libc    ( 1356): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1356): [NET] getaddrinfo-,err=8
D/libc    ( 1356): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1356): [NET] getaddrinfo-, 1
D/libc    ( 1356): [NET] getaddrinfo_proxy+
,V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x5ca4d4b8: I/O error during system call, Connection timed out
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5a63 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1356): [NET] getaddrinfo_proxy-, success
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/libc    ( 1356): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,D/libc    ( 1356): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
D/libc    ( 1356): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(43c49810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43c49810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43c46158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422eb690: PendingIntentRecord{422d1cf0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1879140, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c46158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5258): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5258): ====startRecUseTime====
D/htc.customization.log.level( 5258):  is 
W/CustomizationLogLevel( 5258): Level value is invalid, use default level 2
D/CustomizationManager( 5258):  Read ACC file spent 0.109 (s)
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5258): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5258): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5258): Parsing tag category name = system
I/CustomizationCIDLoader( 5258): Parsing tag category name = application
I/CustomizationCIDLoader( 5258): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5258): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5258): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5258): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5258): Parsing tag category name = Settings
D/CustomizationManager( 5258):  Read CID file spent 0.165 (s)
D/CustomizationManager( 5258):  All configurations done spent 0.165 (s)
W/HtcNativeFlag( 5258): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5258): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5258): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5258): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=5258, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/asset   (  909): Copying FileAsset 0x684cd838 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  909): Skipping PackageSetting{4213f188 com.example.hello/10397} due to missing metadata
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1226): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1349): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): acquireWL(423b5248): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(423b5248): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/VoicemailCleanupService( 1289): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1349): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1349): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsRemoved
W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1326): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 1326): handle notify Blinkfeed plugin client changed
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/IcingCorporaProvider( 2865): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/ExternalAccountType( 1349): Unsupported attribute readOnly
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5272 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  909): acquireWL(437dc658): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(437dc658): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(43782dc8): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2865): UpdateCorporaTask done [took 345 ms] updated apps [took 345 ms] 
E/SQLiteDatabase( 5272): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5272): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5272): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5272): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5272): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5272): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5272): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5272): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5272): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5272): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5272): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5272): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5272): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5272): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5272): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5272): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5272): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5272): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5272): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5272): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5272): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5272): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5272): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5272): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5272): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5272): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5272): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5272): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5272): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5272): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5272): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5272): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5272): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5272): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5272): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5272): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5272): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5272): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5272): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5272): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5272): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5272): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5272): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5272): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5272): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5272): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5272): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5272): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5272): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5272): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5272): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5272): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5272): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5272): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5272): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5272): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5272): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5272): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5272): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5272): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5272): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5272): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5272): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5272): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5272): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5272): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5272): threadid=11: thread exiting with uncaught exception (group=0x4163be30)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5272): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5272): Process: com.google.android.apps.docs, PID: 5272
E/AndroidRuntime( 5272): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5272): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5272): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5272): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5272): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5272): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5272): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5272): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5272): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop151.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 5272): killProcess, pid=5272
D/Process ( 5272): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5290 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  909): Recipient 5272
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 5272) has died.
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 5290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5303 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5290): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5290): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5290): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5290): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5290): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5290): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5290): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5290): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5290): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5290): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5290): threadid=10: thread exiting with uncaught exception (group=0x4163be30)
E/AndroidRuntime( 5290): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5290): Process: com.android.keychain, PID: 5290
E/AndroidRuntime( 5290): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5290): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5290): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5290): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5290): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5290): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5290): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5290): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5290): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.android.keychain
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 5303): getInstance(Context context)
D/Process ( 5290): killProcess, pid=5290
D/Process ( 5290): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450462951631.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  909): Recipient 5290
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 5290) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5303): getInstance(Context context)
D/AppTag  ( 5303): onCreate()
D/PMS     (  909): acquireWL(43797530): PARTIAL_WAKE_LOCK  AsyncService 0x1 4167 10160 null
D/PMS     (  909): releaseWL(43797530): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4194): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2189): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2189): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2189): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2189): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2189): Module APK com.google.android.play.games already loaded
I/ActivityManager(  909): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2189): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2189): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2189): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2189): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca44fa0
E/SQLiteDBG( 2189): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e224490
W/dalvikvm( 2189): threadid=37: thread exiting with uncaught exception (group=0x4163be30)
E/DriveAsyncService( 2189): disk I/O error (code 3850)
E/DriveAsyncService( 2189): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2189): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2189): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2189): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2189): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2189): Process: com.google.android.gms, PID: 2189
E/AndroidRuntime( 2189): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2189): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2189): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2189): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2189): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2189): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2189): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2189): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2189): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2189): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2189): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
D/Process ( 2189): killProcess, pid=2189
D/Process ( 2189): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop153.tmp: open failed: EROFS (Read-only file system)
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
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41afeb30 +
I/Prism.WidgetManager( 1275): onLoadItems() +
I/ActivityManager(  909): Recipient 2189
I/ActivityManager(  909): Process com.google.android.gms (pid 2189) has died.
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10996ms
D/PMS     (  909): handleWLDeath(43782dc8): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10996ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10995ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10994ms
I/ActivityManager(  909): Resuming delayed broadcast
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10986ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10985ms
E/SQLiteLog( 1356): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1356): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f07008
W/dalvikvm( 1356): threadid=1: thread exiting with uncaught exception (group=0x4163be30)
E/AndroidRuntime( 1356): FATAL EXCEPTION: main
E/AndroidRuntime( 1356): Process: com.google.process.gapps, PID: 1356
E/AndroidRuntime( 1356): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1356): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1356): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1356): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1356): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1356): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1356): 	... 10 more
W/PackageManager(  909): Unable to load service info ResolveInfo{4340a7c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/ActivityManager(  909): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop154.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5333 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1356): killProcess, pid=1356
D/Process ( 1356): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 

```
