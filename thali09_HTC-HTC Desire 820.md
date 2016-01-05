#### Test 5507315224df3aa_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system,
D/PMS     (  907): acquireWL(43cd5238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43cd5238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
--------- beginning of /dev/log/main
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 4508): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4508): ====startRecUseTime====
D/htc.customization.log.level( 4508):  is 
W/CustomizationLogLevel( 4508): Level value is invalid, use default level 2
D/CustomizationManager( 4508):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4508): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4508): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4508): Parsing tag category name = system
I/CustomizationCIDLoader( 4508): Parsing tag category name = application
I/CustomizationCIDLoader( 4508): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4508): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4508): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4508): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4508): Parsing tag category name = Settings
D/CustomizationManager( 4508):  Read CID file spent 0.093 (s)
D/CustomizationManager( 4508):  All configurations done spent 0.093 (s)
W/HtcNativeFlag( 4508): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4508): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4508): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4508): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4508
D/PMS     (  907): acquireHCC(43c62a60): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(43c2e2e8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x695f5ad0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1114497968
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4519 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4519): Copying FileAsset 0x5c7a3428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1274): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4519): Binding Chromium to main looper Looper (main, tid 1) {41b2ade8}
I/LibraryLoader( 4519): Expected native library version number "",actual native library version number ""
I/chromium( 4519): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4519): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(43ba4c98): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(43b94048): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425a9930:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4519): 1102319536: getState(). Returning 12
D/PMS     (  907): releaseWL(43ba4c98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4519): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4519): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4519): Local Branch: 
I/Adreno-EGL( 4519): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4519): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4519):                  aa63bbd948f41d15fc72f585e
W/chromium( 4519): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4519): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4519): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4519): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4519): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4519): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4519): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4519): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4519): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4519): CordovaWebView is running on device made by: HTC
W/ResourceType( 4519): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4519): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b72660, mServedView=org.apache.cordova.engine.SystemWebView{41b382c8 VFEDH.C. .F....ID 0,0-720,1134 #64}
W/AwContents( 4519): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1274
,W/IInputConnectionWrapper( 4519): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +231ms (total +264ms)
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/JsMessageQueue( 4519): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4519): JniHelper::setJavaVM(0x41603048), pthread_self() = 1663679288
,D/JX-Cordova( 4519): jxcore cordova android initializing
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 11.625MB for 96598-byte allocation
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 11.706MB for 144892-byte allocation
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 11.821MB for 217334-byte allocation
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 11.998MB for 325996-byte allocation
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 12.272MB for 488990-byte allocation
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 13.279MB for 1100216-byte allocation
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 14.166MB for 1650320-byte allocation
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 15.517MB for 2475476-byte allocation
,I/dalvikvm-heap( 4519): Grow heap (frag case) to 17.536MB for 3713210-byte allocation
,W/jxcore-log( 4519): Initializing JXcore engine
,W/jxcore-log( 4519): JXcore engine is ready
,W/jxcore-log( 4519): Starting JXcore engine
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(43c62a60): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(43c2e2e8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4519): Platform android
W/jxcore-log( 4519): 
,W/jxcore-log( 4519): Process ARCH arm
W/jxcore-log( 4519): 
,I/jxcore-log( 4519): JXcore Cordova bridge is ready!
I/jxcore-log( 4519): 
,W/jxcore-log( 4519): JXcore engine is started
,I/chromium( 4519): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  907): releaseWL(43b94048): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4519): Toggling radios to true
I/jxcore-log( 4519): 
,D/BluetoothAdapter( 4519): enable(): BT is already enabled..!
,D/WifiManager( 4519): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1394
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
D/WifiService(  907): setWifiEnabled: true pid=4519, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/WifiManager( 4519): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4519): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): TDLS: Tear down peers
,I/wpa_supplicant( 1160): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4519): Radios toggled
I/jxcore-log( 4519): 
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiService(  907): New client listening to asynchronous messages
I/jxcore-log( 4519): Received device characteristics:
I/jxcore-log( 4519): Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4519): Bluetooth name: HTC Desire 820
I/jxcore-log( 4519): Device name: HTC-HTC Desire 820
I/jxcore-log( 4519): 
I/jxcore-log( 4519): Perf Test app loaded loaded
I/jxcore-log( 4519): 
I/jxcore-log( 4519): check test folder
I/jxcore-log( 4519): 
I/jxcore-log( 4519): found test : ./testFindPeers.js
I/jxcore-log( 4519): 
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1160): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1160): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1160): TDLS: Remove peers on disassociation
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb89f4bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1160):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1160): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  907): [isWifi] getHotspotEnabled: false
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
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized,
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
D/wpa_supplicant( 1160): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1160): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
I/jxcore-log( 4519): found test : ./testSendData.js
I/jxcore-log( 4519): 
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(41fd5388): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907):    returned true
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20175 mDataStallAlarmIntent=null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): Fast associate: Old scan results
I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WISPrService( 3850): >>>>>WISPrService start isConnected = false<<<<<
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907):    returned true
,D/WISPrService( 3850): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  907): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiNative-wlan0(  907): doBoolean: SET pno 1
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
,V/NativeCrypto( 1361): Read error: ssl=0x66342e00: I/O error during system call, Connection timed out
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): CTRL_IFACE SET 'pno'='1'
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/PMS     (  907): acquireWL(42494ac0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x66342e00: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:4   entry:0xb88298e0  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb882a178  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb882e090  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb882e4f0  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb882e190  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb882e348  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb882e428  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb8829ff8  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb882e640  removed 
D/libc    (  363): [NET] entry_id:10   entry:0xb882a2f8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/WISPrService( 3850): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3850): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
D/PMS     (  907): acquireWL(4276d0c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1160): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/WifiNative-wlan0(  907):    returned true
D/wpa_supplicant( 1160): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
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
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): selected network = 1
D/wpa_supplicant( 1160): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb89f64e8  current_ssid=0x0
D/wpa_supplicant( 1160): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1160): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1160): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1160): check if in concurrent case
I/wpa_supplicant( 1160): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1361/10029)
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1780
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1160): RSN: PMKSA cache search - network_ctx=0xb89f64e8 try_opportunistic=0
D/wpa_supplicant( 1160): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1160): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1160): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/wpa_supplicant( 1160): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1160): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1160): nl80211: Unsubscribe mgmt frames handle 0xb89f5718 (mode change)
D/wpa_supplicant( 1160): nl80211: Subscribe to mgmt frames with non-AP handle 0xb89f5718
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb89f5718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1160):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1160):   * freq=2412
D/wpa_supplicant( 1160):   * Auth Type 0
D/wpa_supplicant( 1160):   * WPA Versions 0x2
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
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
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (376) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-47
I/wpa_supplicant( 1160): tsf=0000000022100288
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-55
I/wpa_supplicant( 1160): tsf=0000000116837458
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-78
I/wpa_supplicant( 1160): tsf=0000000022100306
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  907): releaseWL(42494ac0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4276d0c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
D/WifiStateMachine(  907): == begin of scan result ==
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/WifiStateMachine(  907): == (3) end of scan result ==
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1160): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
D/WifiManager( 1225): getScanResults enter 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1160): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1160): Failed to initiate AP scan
I/wpa_supplicant( 1160): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  907):    returned true
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 22100288, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 116837458, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 22100306, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): add 3 to mScanResults
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
I/chromium( 4519): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
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
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  907): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1160): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1160): Add randomness: count=7 entropy=1
,I/wpa_supplicant( 1160): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1160): TDLS: Remove peers on association
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=1
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1160): EAPOL: enable timer tick
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1160): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1160): Get randomness: len=32 entropy=2
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/wpa_supplicant( 1160): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb89f59f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1160):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1160): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa8b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1160):    broadcast key
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1160): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1160): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1160): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1160): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1160): set send_ind_to_ndc = 0
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1160): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1160): EAPOL authentication completed successfully
I/wpa_supplicant( 1160): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 79
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WISPrService( 3850): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3850): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 1
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1160): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(441fd178): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42633990 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42633990 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4581 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/PMS     (  907): acquireWL(43067118): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(43067118): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1569/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTING
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4340/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4340/10100)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/MusicStore( 4581): Database version: 95
,W/ContextImpl( 4581): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4581): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/wpa_supplicant( 1160): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1160): EAPOL: disable timer tick
,W/ContextImpl( 4581): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4581): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4581): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4581, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4581): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,I/MediaRouter( 4581): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4581/10154)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2447/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4601 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4581): getSelectedRoute
,I/NetworkMonitor( 4581): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4581/10154)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4581, uid=10154, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(436508b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/Process (  907): killProcessQuiet, pid=4276
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4601): ACRA is enabled for com.facebook.katana, intializing...
D/PMS     (  907): releaseWL(436508b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  907): Killing 4276:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/ACRA    ( 4601): Looking for error files in /data/data/com.facebook.katana/app_acra-reports,
,D/ACRA    ( 4601): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  907): Recipient 4276
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4601): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4601): Preparing secondary program dexes.
V/DexLibLoader( 4601): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4601): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4601): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4601): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4601): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4601): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4601): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4601): Dex already copied
D/OdexVerifier( 4601): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4601): Creating class loader
,V/DexLibLoader( 4601): Finished creating class loader
V/DexLibLoader( 4601): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4601): Dex already copied
D/OdexVerifier( 4601): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4601): Creating class loader
,V/DexLibLoader( 4601): Finished creating class loader
V/DexLibLoader( 4601): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4601): Dex already copied
D/OdexVerifier( 4601): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4601): Creating class loader
,V/DexLibLoader( 4601): Finished creating class loader
V/DexLibLoader( 4601): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4601): Dex already copied
D/OdexVerifier( 4601): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4601): Creating class loader
,V/DexLibLoader( 4601): Finished creating class loader
,V/DexLibLoader( 4601): Verifying classes from secondary dexes.
,D/DexLibLoader( 4601): DexLibLoader.ensureDexLoaded took 18 ms
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(441fd178): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1160): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  907): WAN detection
,D/WISPrService( 3850): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@42409b80
,D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
,D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(43920df0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43920df0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/dalvikvm( 4601): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4601): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4601): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4601): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4601): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4601): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4601): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4601): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4601): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4601): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4601): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4601): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4601): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4601): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4172
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4172:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AutoSetting( 1346): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4652 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1346): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1346): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1346/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1346/10055)
D/AutoSetting( 1346): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1346): service - onStartCommand() check timezone in 30000
,W/fb4a(:<default>):UserScope( 4601): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4601): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4652): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4652): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4652): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4652): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
W/fb4a(:<default>):UserScope( 4601): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4666 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=4309
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4309:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4652/10079)
I/ActivityManager(  907): Recipient 4172
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4309
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4652/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4652/10079)
,D/PMS     (  907): acquireWL(42fe2898): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426d4a40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1452008671614 min interval config: 0 actual interval: 50132
D/PMS     (  907): releaseWL(42fe2898): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(41fd5388): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,I/CheckinService( 2183): Checking schedule, now: 1452008721757 next: 1452008701589
,I/CheckinService( 2183): active receiver: enabled
D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2183, uid=10029, userID:0
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4682 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4340
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/CheckinService( 2183): Preparing to send checkin request
,I/EventLogService( 2183): Accumulating logs since 1452008664526
I/ActivityManager(  907): Killing 4340:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
I/ActivityManager(  907): Recipient 4340
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 4581): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1569/10029)
D/PMS     (  907): acquireWL(42c99818): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(42c99818): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3971/10053)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4581/10154)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4652/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1569/10029)
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=25 [4][1][0]
D/PMS     (  907): acquireWL(434abc10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  907): releaseWL(434abc10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4601): Grow heap (frag case) to 9.954MB for 84664-byte allocation
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4682): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
W/ContextImpl( 4682): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
E/ExternalAccountType( 1331): Unsupported attribute readOnly
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
W/GAV2    ( 4682): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4682): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4682): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4601): Grow heap (frag case) to 9.968MB for 28144-byte allocation
E/dalvikvm( 4601): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4601): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4601): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4601): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4601): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4601): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4601): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4601): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4601): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4601): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4601): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4601): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4601): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4601): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4601): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4601): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4601): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4601): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4601): Grow heap (frag case) to 10.014MB for 39954-byte allocation
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4601): Grow heap (frag case) to 10.090MB for 79892-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4682/10151)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,V/WebViewChromiumFactoryProvider( 4682): Binding Chromium to main looper Looper (main, tid 1) {41b301b8}
,I/LibraryLoader( 4682): Expected native library version number "",actual native library version number ""
,I/chromium( 4682): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4682): Initializing chromium process, renderers=0
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  907): acquireWL(4352f0b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(43c9e9b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  907): releaseWL(43c9e9b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 4682): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4682): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4682): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4682): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4682): Local Branch: 
I/Adreno-EGL( 4682): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4682): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4682):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4682): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4682/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4682/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): killProcessQuiet, pid=4363
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3656/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3656/10160)
,I/ActivityManager(  907): Killing 4363:com.htc.backup/1000 (adj 15): empty #17
I/dalvikvm-heap( 4601): Grow heap (frag case) to 10.275MB for 75760-byte allocation
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/ActivityManager(  907): Recipient 4363
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4719 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43010b50 u0 ReceiverList{423bb298 4601 com.facebook.katana/10027/u0 remote:422b9c98}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43010b50 u0 ReceiverList{423bb298 4601 com.facebook.katana/10027/u0 remote:422b9c98}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42a55918 u0 ReceiverList{423b29f8 4601 com.facebook.katana/10027/u0 remote:4222dfd8}}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2447/10021)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,W/dalvikvm( 4719): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4719): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4719): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4719): install
,I/MultiDex( 4719): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4719): loading existing secondary dex files
,I/MultiDex( 4719): load found 3 secondary dex files
,I/MultiDex( 4719): install done
,W/dalvikvm( 4719): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4719): VFY: unable to resolve instance field 36
,W/dalvikvm( 4719): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4719): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PMS     (  907): acquireWL(43d72dd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1346): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  907): releaseWL(43d72dd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/MobileConnectivityChangeReceiver( 4652): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4652): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1346): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1346): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1346/10055)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1346/10055)
D/AutoSetting( 1346): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1346): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4682/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3656/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3656/10160)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43d31c18): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1452008671614 min interval config: 0 actual interval: 50750
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43d31c18): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4601): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4601): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ProviderInstaller( 4719): Installed default security provider GmsCore_OpenSSL
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4601): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,W/dalvikvm( 4719): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4719): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/MDM     ( 1225): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2183): Restart initialization of location
,W/dalvikvm( 4719): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
E/dalvikvm( 4719): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4719): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 4719): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4719): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  907): acquireWL(425f5b00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(425f5b00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4719): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2628344960
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1159223831
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 4719): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4719): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4719): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4719): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4719): Local Branch: 
I/Adreno-EGL( 4719): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4719): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4719):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4719): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4719): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4719): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4719): Local Branch: 
I/Adreno-EGL( 4719): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4719): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4719):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4719/10029)
,I/Adreno-EGL( 4719): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4719): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4719): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4719): Local Branch: 
I/Adreno-EGL( 4719): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4719): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4719):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2183): [NET] getaddrinfo-, 1
,D/libc    ( 2183): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5fcf +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 232
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2183): [NET] getaddrinfo_proxy-, success
,W/dalvikvm( 4519): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4519): threadid=1: thread exiting with uncaught exception (group=0x416fbe30)
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =580f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,E/ActivityManager(  907): App crashed! Process: com.test.thalitest
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
E/AndroidRuntime( 4519): FATAL EXCEPTION: main
E/AndroidRuntime( 4519): Process: com.test.thalitest, PID: 4519
E/AndroidRuntime( 4519): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4519): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4519): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4519): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4519): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4519): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4519): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4519): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4519): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4519): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4519): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4519): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4519): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4519): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4519): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4519): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4519): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4519): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4519): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  907):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  907): killProcessQuiet, pid=4327
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/Process ( 4519): killProcess, pid=4519
D/Process ( 4519): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Killing 4327:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  907): Recipient 4327
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,I/CheckinTask( 2183): Sending checkin request (12085 bytes)
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4519 uid 10389
,I/ActivityManager(  907): Recipient 4519
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  907): WIN DEATH: Window{4216b5c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  907): Process com.test.thalitest (pid 4519) has died.
,D/WifiService(  907): Client connection lost with reason: 4
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/AutoSetting( 1522): service - handleMessage() stop self
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=14 [21][3][0]
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,W/fb4a(:<default>):UserScope( 4601): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4601): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/CheckinTask( 2183): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
I/CheckinService( 2183): Checking schedule, now: 1452008724583 next: 1452531661579
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,I/CheckinService( 2183): Checking schedule, now: 1452008724610 next: 1452531661579
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/CheckinService( 2183): Recording last checkin time for package unspecified as 1452008724617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(426d4a40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/PMS     (  907): acquireWL(43500b70): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
,D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4f1c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4601): Called registerBroadcastReceiver twice.
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027),
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/PMS     (  907): acquireWL(438189b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/PMS     (  907): releaseWL(43500b70): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(438189b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42417800): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(42417800): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4352f0b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(42650398): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4581 10154 null
,W/ContextImpl( 4581): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4581, uid=10154, userID:0
,I/MusicLeanback( 4581): Conditions not met for autocaching.
,I/MusicLeanback( 4581): Stop autocaching.
,W/ContextImpl( 4581): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  907): releaseWL(42650398): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43516510 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=10 [10][1][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4682): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  907): killProcessQuiet, pid=4380
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4380:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4380
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4778 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false,
W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/Launcher( 1274): Deferring update until onResume
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/Launcher( 1274): waitUntilResume // bindAppsUpdated
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/dalvikvm( 4778): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4778): VFY: unable to resolve instance field 36
,W/dalvikvm( 4778): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4778): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel   ( 4778): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4778): MmsConfig.loadMmsSettings
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4778, uid=10111, userID:0
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4801 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,W/Settings( 4778): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4778, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4778, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4778, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4778, uid=10111, userID:0
,W/PackageManager(  907): Unable to load service info ResolveInfo{426f6148 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4778, uid=10111, userID:0
D/PMS     (  907): acquireWL(43a3efb8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4778 10111 null
,D/MessageFrequencyProvider( 4801): onCreate
,V/GetPrviateResource( 4801): GetPrviateResource
,V/GetPrviateResource( 4801): GetPrviateResource
,D/MmsCustomizationProvider( 4801): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/ProviderInstaller( 4778): Installed default security provider GmsCore_OpenSSL
,I/IcingCorporaProvider( 2824): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/[PluginManager]RegisterService( 1346): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1346): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/MmsCustomizationProvider( 4801): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/PMS     (  907): releaseWL(43a3efb8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(440ca6e0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  907): killProcessQuiet, pid=3971
,I/ActivityManager(  907): Killing 3971:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/Babel   ( 4778): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4778): MmsConfig.loadFromDatabase
D/PMS     (  907): acquireWL(431cd6f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3656 10160 null
D/PMS     (  907): releaseWL(440ca6e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(431cd6f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 3971
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Babel   ( 4778): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4778): MmsConfig.loadFromResources
,E/Babel   ( 4778): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4778): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Process (  907): killProcessQuiet, pid=3893
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  907): acquireWL(43467328): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Killing 3893:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/MessageCustFlag( 4801): sense_version=6.0
,D/BTAccessoryUtil( 4801): createReceiver
,D/BTAccessoryUtil( 4801): registerReceiver return intent = null
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/MessageCustFlag( 4801): sku_id=99
,W/SystemReader( 4801): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3893
I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
D/Messaging( 4801): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4801): networkCode: 
D/MessageCustFlag( 4801): sku_id=99
D/MmsConfig( 4801): SIE smsPri: null
D/MmsConfig( 4801): networkCode: 
D/HtcTelephonyCapability( 4801): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4801): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4801): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4801): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  907): Resuming delayed broadcast
,I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  907): acquireWL(43495ac8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43495ac8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/LocationProviderProxy(  907): applying state to connected service
,D/PMS     (  907): acquireWL(4325ea48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4325ea48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43be14b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43be14b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43d263d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43d263d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2824): UpdateCorporaTask done [took 497 ms] updated apps [took 497 ms] 
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41bbecd8 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(43467328): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4399a100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/BatteryService(  907): n_update end
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4399a100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41bbecd8 -
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1244): -- N1 =0
,D/PhoneApp( 1244): -- N2 =0
,D/PhoneApp( 1244): -- N3 =0
,D/Messaging( 4801): mNeedToUpdateDate2 start
,D/MmsConfig( 4801): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4801): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4801): 
D/MmsAsyncWorkHandler( 4801): HM tk = 20001
,D/ReportIndicatorCache( 4801): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4801): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b3c2a8
,I/Messaging( 4801): mccmnc> 
D/DraftCache( 4801): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4801): [DraftCache/1] refresh
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1244):  phoneType = -1
D/MmsConfig( 4801): networkCode: 
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4801): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4801): sense_version=6.0
,D/Jerry   ( 4801): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4801): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4801): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4801): createReceiver
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4801): mNeedToUpdateDate2: false
,D/TelephUtils( 1244): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,V/MmsProvider( 1244): Update uri=content://mms, match=0
,V/MmsProvider( 1244): selection=st=129 AND m_type!=134
D/Messaging( 4801): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4801): TransactionService is going to be woken up.
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 70
,D/AccFlag ( 1244): sku_id=99
,V/TransactionService( 4801): 1-Creating TransactionService
V/TransactionService( 4801): onStartCommand: 1
,D/MmsSystemEventReceiver( 4801): unRegisterForConnectionStateChanges
V/TransactionService( 4801): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4801): Loading previous transactions.
,D/DraftCache( 4801): [DraftCache/475] rebuildCache
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 70
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1244): device_type: 1
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TransactionService( 4801): Force set service start id to 1
V/TransactionService( 4801): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4801): unRegisterForConnectionStateChanges
D/Messaging( 4801): ViewCache CreatePreload
,D/Messaging( 4801): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TransactionService( 4801): stopSelfResult: true, mLastHandledServiceId: 1
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 70
,D/Jerry   ( 1244): URI_DRAFT
,D/Messaging( 4801): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,V/TransactionService( 4801): Destroying TransactionService
,D/Cust_MMSMS( 4801): _has_set_default_values_2=true
,V/TransactionService( 4801): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/DraftCache( 4801): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4801): [DraftCache/475] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4801): 
D/MmsAsyncWorkHandler( 4801): HM tk = 20002
,D/MsgPreferenceUtils( 4801): def_index: 0
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1244): sku_id=99
,D/MsgPreferenceUtils( 4801): globalIndex = 1
D/MsgPreferenceUtils( 4801): phone state: true
D/MsgPreferenceUtils( 4801): sd state: false
,D/MsgPreferenceUtils( 4801): vIndex = 0
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 70
,D/AccFlag ( 1244): sku_id=99
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,I/GAV4    ( 4778): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(44213548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{4304c400: PendingIntentRecord{4241e180 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=137294, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{426b2ae0: PendingIntentRecord{426f86d8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138957, Int=0
,D/PMS     (  907): acquireWL(441d4900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=20 [5][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(44192e98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44192e98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(441d4900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(441755f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44213548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(441755f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(441648e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): acquireWL(441261e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(441081f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1225): Vacuum at: now=1452008741126 tag=VacuumService
,D/PMS     (  907): releaseWL(441648e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(44107508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(44107508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(441081f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42226520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(441261e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(42226520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42490008): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(42490008): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4233c9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(4233c9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/AutoSetting( 1346): service - mHandler: update timezone
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1522): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1557): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1522): service - mHandler: update timezone
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1522): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1522): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1119): removeNotification.gc:58
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e8e138 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 4 8 3 11
,D/AutoSetting( 1346): service - mHandler: update timezone
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/DotMatrix( 1557): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1522): service - mHandler: update timezone
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1522): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1522): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1346): service - handleMessage() stop self
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/AutoSetting( 1346): service - onDestroy() END
,D/AutoSetting( 1346): service - handleMessage() quit looper
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ead5b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 9 2 11
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  907): acquireWL(42543438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42543438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=4417
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4417:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4417
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43859310 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43520e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43520e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1522): service - handleMessage() stop self
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4431
,I/ActivityManager(  907): Killing 4431:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4431
,D/PMS     (  907): acquireWL(423fdd98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{43c5e6e0: PendingIntentRecord{438b3a90 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=182687, Int=0
,D/PMS     (  907): releaseWL(423fdd98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(42771910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42771910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(424cde80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{41fabcd0: PendingIntentRecord{4241e180 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=197306, Int=0
,D/PMS     (  907): releaseWL(424cde80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42179cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [4][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4250f148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4250f148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42179cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4251d240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(4251d240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4382f160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4240cd18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4382f160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 14087 seconds from now (1452008799973)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d36b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 166
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4240cd18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(441077a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(441077a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43c6b348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(43c6b348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ClearcutLoggerApiImpl( 1361): disconnect managed GoogleApiClient
,D/PMS     (  907): acquireWL(439fb1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=218017, Int=0
,D/PMS     (  907): releaseWL(439fb1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4316f5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4316f5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42692ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42692ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(43d75978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=278017, Int=0
,D/PMS     (  907): releaseWL(43d75978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43034bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43034bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43ba01a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=338018, Int=0
,D/PMS     (  907): releaseWL(43ba01a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43832880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43832880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(430f50e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=398018, Int=0
,D/PMS     (  907): releaseWL(430f50e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(436ba668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(436ba668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4244b768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=458018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4244b768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(440dd818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440dd818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43171fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=518018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43171fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(438086f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(438086f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43711170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=578018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43711170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44209b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44209b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  907): acquireWL(4320ca48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=638018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4320ca48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=4084
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4084:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4084
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(426999c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426999c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4421d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=698018, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4421d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(439fdce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(439fdce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(431787a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(431787a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(427b7048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=758017, Int=0
,D/PMS     (  907): releaseWL(427b7048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c6a890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c6a890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42707290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=818017, Int=0
,D/PMS     (  907): releaseWL(42707290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425b8428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425b8428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(434a6d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=878017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(434a6d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4355bbe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4355bbe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(442174b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(442174b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4367d270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=938018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4367d270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43cc1560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cc1560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/ContextImpl( 4478): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3850): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3850): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3850): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3850): Cust_ConnectToPC   : spcsc>false
D/        ( 3850): Cust_ConnectToPC   : IPT>true
D/        ( 3850): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3850): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3850): Index of the first 1 = 3
W/ContextImpl( 3850): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3850): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3850): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3850): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3850): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3850): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3850): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43820008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=998017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.700MB for 50416-byte allocation
D/PMS     (  907): releaseWL(43820008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4351c5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41dd0348: PendingIntentRecord{424c2aa8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=797129, Int=0
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4896 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{424d3350: PendingIntentRecord{4269fa50 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452008817138, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{437c6850: PendingIntentRecord{426234f0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452009103203, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{42454c48: PendingIntentRecord{426fb818 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452009537565, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{42fe2e28: PendingIntentRecord{42765dc8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452009610848, Int=0
,D/PMS     (  907): acquireWL(433d7378): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4478): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(431ea3c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(433d7378): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4478): call getInstance()
,D/SmartSyncUtils( 4478): isEpsOn(), nState = 0
,D/PMS     (  907): acquireWL(441219e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4478 1000 null
,D/PowerUsageList:PowerUsageHelper( 4478): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4478): [updateNmRange] bManual = false
,I/EventLogService( 2183): Aggregate from 1452008721851 (log), 1452007303165 (data)
,D/SmartSyncScreenOnOffTimeReceiver( 4478): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4478): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4478): SettingOnTime = 1452060000000, randomSettingOnTime = 1452056541000
,D/SmartSyncScreenOnOffTimeReceiver( 4478): SettingOffTime = 1452045600000, randomSettingOffTime = 1452048631000
,D/SmartSyncScreenOnOffTimeReceiver( 4478): bDayMode = false
,D/PMS     (  907): releaseWL(4351c5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4478): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4478): bNightModeTurnOffOnce = false
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): releaseWL(441219e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4896/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,D/PMS     (  907): releaseWL(431ea3c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Process (  907): killProcessQuiet, pid=4454
,I/ActivityManager(  907): Killing 4454:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4454
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(44181438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/BatteryService(  907): n_update end
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(44181438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4416f0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{43d10670: PendingIntentRecord{426ef320 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1022985, Int=0
,D/PMS     (  907): acquireWL(44167218): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44167218): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4416f0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44166150): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024814
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024868
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024876
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024879
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026427
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026441
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360032433,
,D/PMS     (  907): releaseWL(44166150): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100,
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=9 [87][8][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(44106fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(44106fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43ca7b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1058017, Int=0
,D/PMS     (  907): releaseWL(43ca7b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c56660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  907): releaseWL(43c56660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43904488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43904488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43760108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1118018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43760108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43679530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43679530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(434abab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(434abab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43496e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1178018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43496e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(427b6570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(427b6570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424396d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424396d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(41e7b810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1238017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41e7b810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(424a7458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424a7458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  907): Start proc com.htc.cs.dm for service com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService: pid=4920 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  907): acquireWL(4244b250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10098}
,V/AlarmManager(  907): sending alarm PendingIntent{4248c850: PendingIntentRecord{426af380 com.htc.cs.dm startService}}, i=com.htc.cs.action.EXECUTE_WORKFLOW, t=1, cnt=1, w=1452009859788, Int=0
,D/PMS     (  907): releaseWL(4244b250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10098}
,I/DeviceManagement( 4920): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4920 dbg=false s=true
,I/DeviceManagement( 4920): WorkflowService: Starting workflow service
,I/DeviceManagement( 4920): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@41b55b28] args=[Bundle[mParcelledData.dataSize=60]]
I/DeviceManagement( 4920): UpdateWorkflow: ==================================================
I/DeviceManagement( 4920): UpdateWorkflow: TTL update...
,I/DeviceManagement( 4920): UpdateWorkflow: ==================================================
,I/DeviceManagement( 4920): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4920): SessionStateController: Checking invariants...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,I/DeviceManagement( 4920): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 4920): SessionStateController: Checking invariants...
,D/libc    ( 4601): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4601): [NET] getaddrinfo-,err=8
D/libc    ( 4601): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4601): [NET] getaddrinfo-, 1
D/libc    ( 4601): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =91dc +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/DeviceManagement( 4920): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 54
D/libc    (  363): [NET]res_nsend:resplen=74
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4601): [NET] getaddrinfo_proxy-, success
I/global  ( 4601): call createSocket() return a new socket.
D/libc    ( 4601): [NET] getaddrinfo+,hn 10(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4601): [NET] getaddrinfo-, SUCCESS
,I/DeviceManagement( 4920): Perf: *** Cache update - start...
I/DeviceManagement( 4920): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 4920): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4920): Perf: *** Enabled app cache update - complete: 1 ms
I/DeviceManagement( 4920): Perf: *** Config cache update - start...
I/DeviceManagement( 4920): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 4920): ConfigCacheController: *** Updating stale config cache entries...
,D/libc    ( 4601): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4601): [NET] getaddrinfo-,err=8
W/dalvikvm( 4920): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
,W/dalvikvm( 4920): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 4920): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,W/System.err( 4920): Starting the internal HTTP client
,I/DeviceManagement( 4920): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
,I/dalvikvm-heap( 4601): Grow heap (frag case) to 10.972MB for 32784-byte allocation
,D/PMS     (  907): acquireWL(424f7ed0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4601 10027 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
,I/DeviceManagement( 4920): DeviceClientResource: Active network...
I/DeviceManagement( 4920):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=15 [32][5][0]
,I/wpa_supplicant( 1160): Change stage from stage0 to stage3
D/BuildInfo( 4920): Created new instance: com.htc.cs.lib.hms.BuildInfo@41db5da8
,I/DeviceManagement( 4920): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/libc    ( 4920): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4920): [NET] getaddrinfo-, 1
,D/libc    ( 4920): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4920): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4601/10027)
,D/libc    ( 4920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4920): [NET] getaddrinfo-,err=8
D/libc    ( 4920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4920): [NET] getaddrinfo-, 1
,D/libc    ( 4920): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3d3a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/global  ( 4601): I/O error closing connection
I/global  ( 4601): java.net.SocketException: Socket is closed
I/global  ( 4601): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4601): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4601): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4601): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4601): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4601): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4601): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4601): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4601): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4601): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4601): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4601): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4601): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4601): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4601): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4601): Removing a connection that never existed!
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=204
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4920): [NET] getaddrinfo_proxy-, success
D/PMS     (  907): releaseWL(424f7ed0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/DeviceManagement( 4920): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4920): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4920): DeviceClientResourceController: handleDirectives: []
W/dalvikvm( 4920): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 4920): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 4920): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4920): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 4920): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 4920): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
,W/dalvikvm( 4920): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4920): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4920): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4920): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 4920): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4920): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 4920): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4920): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 4920): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 4920): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 4920): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 4920): isCompatible false
I/System.out( 4920): createObjectMapper
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
,I/System.out( 4920): isCompatible false
,I/DeviceManagement( 4920): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 4920): DeviceClientResource: Active network...
I/DeviceManagement( 4920):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [16][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
,D/libc    ( 4920): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4920): [NET] getaddrinfo-, 1
,D/libc    ( 4920): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4920): [NET] getaddrinfo_proxy-, success
D/libc    ( 4920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4920): [NET] getaddrinfo-,err=8
D/libc    ( 4920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4920): [NET] getaddrinfo-, 1
,D/libc    ( 4920): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9da9 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4920): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4920): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4920): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4920): DeviceClientResourceController: handleDirectives: []
I/System.out( 4920): isCompatible false
I/System.out( 4920): createObjectMapper
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
,I/System.out( 4920): isCompatible false
,I/System.out( 4920): isCompatible false
,I/DeviceManagement( 4920): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
,I/DeviceManagement( 4920): DeviceClientResource: Active network...
I/DeviceManagement( 4920):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=12 [8][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (4920/10098)
,D/libc    ( 4920): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4920): [NET] getaddrinfo-, 1
,D/libc    ( 4920): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4920): [NET] getaddrinfo_proxy-, success
D/libc    ( 4920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4920): [NET] getaddrinfo-,err=8
D/libc    ( 4920): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4920): [NET] getaddrinfo-, 1
,D/libc    ( 4920): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =abff +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4920): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4920): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4920): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4920): DeviceClientResourceController: handleDirectives: []
I/System.out( 4920): isCompatible false
I/System.out( 4920): createObjectMapper
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
I/System.out( 4920): isCompatible false
,I/System.out( 4920): isCompatible false
,I/DeviceManagement( 4920): ConfigCacheController: *** Update config cache: updating 3 entries...
,I/DeviceManagement( 4920): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 4920): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 4920): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 4920): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4920): AlarmController: Scheduling TTL alarm for: 2016.01.06 at 17:04:24.036 CET (due to: com.htc.launcher)
,I/DeviceManagement( 4920): Perf: *** Config cache update - complete: 3837 ms
,I/DeviceManagement( 4920): Perf: *** Cache update - complete: 3839 ms
,I/DeviceManagement( 4920): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@41b55b28]
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4920, uid=10098, userID:0
I/DeviceManagement( 4920): WorkflowService: Stopping workflow service
,D/Process (  907): killProcessQuiet, pid=4652
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4652:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4652
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4262b470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(4262b470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42683360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1298018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42683360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4352ed28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4352ed28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43cb3e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(43cb3e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42735640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1358017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42735640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4244eb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4244eb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41c56870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41c56870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(430871d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1418017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(430871d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41cd0848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41cd0848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4418c748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4418c748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(426d0ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1478018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426d0ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42359a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42359a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(431c1ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(431c1ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(440c9400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1538017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440c9400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b65210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b65210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43cde3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cde3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4348e430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1598018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4348e430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425f9600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425f9600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(423e8700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(423e8700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43ba01a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1658018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43ba01a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(426879c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426879c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43518690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43518690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(426d4d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1718017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426d4d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42601838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42601838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42404858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1778018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42404858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4382f768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(4382f768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(4273a5f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4273a5f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(43ccd910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1838017, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false),
,I/ProcessStatsService(  907): Prepared write state in 35ms
,D/PMS     (  907): releaseWL(43ccd910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2016-01-04-23-37-00.bin
,D/PMS     (  907): acquireWL(425ad048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(425ad048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43247230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43247230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(44172188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42355598: PendingIntentRecord{422f4d58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1898018, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44172188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(434a8138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(434a8138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4973): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4973): ====startRecUseTime====
D/htc.customization.log.level( 4973):  is 
W/CustomizationLogLevel( 4973): Level value is invalid, use default level 2
D/CustomizationManager( 4973):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4973): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4973): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4973): Parsing tag category name = system
I/CustomizationCIDLoader( 4973): Parsing tag category name = application
I/CustomizationCIDLoader( 4973): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4973): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4973): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4973): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4973): Parsing tag category name = Settings
D/CustomizationManager( 4973):  Read CID file spent 0.111 (s)
D/CustomizationManager( 4973):  All configurations done spent 0.111 (s)
W/HtcNativeFlag( 4973): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4973): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4973): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4973): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4973, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=4581
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  907): killProcessQuiet, pid=4682
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  907): killProcessQuiet, pid=4666
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  907): Killing 4581:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  907): Killing 4682:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
I/ActivityManager(  907): Killing 4666:com.android.chrome/u0a96 (adj 15): empty for 1803s
W/asset   (  907): Copying FileAsset 0x660d76f0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  907): Recipient 4581
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 4581): Died!
I/ActivityManager(  907): Recipient 4666
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  907): Skipping PackageSetting{4229bde0 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  907): acquireWL(44125d58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(44125d58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Launcher( 1274): Deferring update until onResume
D/Launcher( 1274): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SQLiteConnectionPool( 2183): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  907): Recipient 4682
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  907):   Scheme: "smsto"
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
E/ExternalAccountType( 1331): Unsupported attribute readOnly
W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/[PluginManager]RegisterService( 1346): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1346): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/IcingCorporaProvider( 2824): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4988 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  907): acquireWL(4381f898): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2824): UpdateCorporaTask done [took 106 ms] updated apps [took 106 ms] 
W/PackageManager(  907): Unable to load service info ResolveInfo{41e16118 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4988): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4988): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4988): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4988): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4988): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4988): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4988): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4988): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4988): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4988): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4988): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4988): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4988): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4988): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4988): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4988): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4988): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4988): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4988): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4988): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4988): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4988): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4988): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4988): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4988): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4988): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4988): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4988): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4988): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4988): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4988): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4988): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4988): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4988): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4988): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4988): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4988): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4988): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4988): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4988): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4988): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4988): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4988): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4988): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4988): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4988): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4988): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4988): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4988): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4988): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4988): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4988): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4988): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4988): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4988): threadid=11: thread exiting with uncaught exception (group=0x416fbe30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4988): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4988): Process: com.google.android.apps.docs, PID: 4988
E/AndroidRuntime( 4988): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4988): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4988): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4988): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4988): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4988): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4988): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4988): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4988): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4988): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4988): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4988): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4988): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4988): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4988): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4988): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4988): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4988): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4988): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4988): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4988): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4988): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4988): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4988): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4988): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4988): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4988): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4988): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4988): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4988): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4988): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4988): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4988): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4988): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4988): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4988): Opened ClientFlag.db in read-only mode
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5006 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4988): killProcess, pid=4988
D/Process ( 4988): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
I/ActivityManager(  907): Recipient 4988
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4988) has died.
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 5006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5006): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5006): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5006): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5006): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5006): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5006): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5006): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5006): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5006): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5006): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5006): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5006): threadid=10: thread exiting with uncaught exception (group=0x416fbe30)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5020 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 5006): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5006): Process: com.android.keychain, PID: 5006
E/AndroidRuntime( 5006): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5006): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5006): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5006): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5006): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5006): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5006): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5006): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5006): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/Process ( 5006): killProcess, pid=5006
D/Process ( 5006): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452010526718.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 5006
I/ActivityManager(  907): Process com.android.keychain (pid 5006) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5020): getInstance(Context context)
D/AppTag  ( 5020): getInstance(Context context)
D/AppTag  ( 5020): onCreate()
D/PMS     (  907): acquireWL(42771ad8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3656 10160 null
D/PMS     (  907): releaseWL(42771ad8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4126): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2183): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2183): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x654b9ae0
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6dca6488
W/dalvikvm( 2183): threadid=44: thread exiting with uncaught exception (group=0x416fbe30)
E/DriveAsyncService( 2183): disk I/O error (code 3850)
E/DriveAsyncService( 2183): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2183): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2183): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2183): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2183): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2183): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
D/Process ( 2183): killProcess, pid=2183
E/AndroidRuntime( 2183): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2183): Process: com.google.android.gms, PID: 2183
E/AndroidRuntime( 2183): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2183): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2183): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2183): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2183): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2183): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2183): 	at java.lang.Thread.run(Thread.java:864)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2183): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
D/PMS     (  907): acquireWL(434af090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41dd0348: PendingIntentRecord{424c2aa8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1728886, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{41fd82c0: PendingIntentRecord{42616638 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821268, Int=1800000
V/AlarmManager(  907): sending alarm PendingIntent{42390ec0: PendingIntentRecord{427376d8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1857225, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{42650088: PendingIntentRecord{426ef320 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1925030, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{42454c48: PendingIntentRecord{426fb818 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452010437565, Int=900000
I/ActivityManager(  907): Recipient 2183
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms (pid 2183) has died.
D/WifiService(  907): Client connection lost with reason: 4
D/PMS     (  907): handleWLDeath(4381f898): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20996ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20994ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20993ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20990ms
E/SQLiteLog( 1361): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1361): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x640087d8
W/dalvikvm( 1361): threadid=1: thread exiting with uncaught exception (group=0x416fbe30)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1361): FATAL EXCEPTION: main
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
D/Process ( 1361): killProcess, pid=1361
D/Process ( 1361): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 4920): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4920): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4920): WorkflowService: Starting workflow service
I/DeviceManagement( 4920): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@42212788] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4920): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4920): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4920): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4920): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4920): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 4920): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4920): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5caa1228
W/DeviceManagement( 4920): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@42212788]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 4920): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 4920): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 4920): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4920): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4920): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4920): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4920): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4920): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4920): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4920): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4920): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5052 uid=10099 gids={50099, 3003, 5012}
D/Documents( 5052): Loading roots for com.android.providers.downloads.documents
D/Documents( 5052): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5052): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5052): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5052): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5052): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5052): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5052): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5052): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5052): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5052): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5052): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5052): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5052): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5052): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5052): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5052): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5052): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5052): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5052): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5052): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5052): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5052): threadid=1: thread exiting with uncaught exception (group=0x416fbe30)
I/ActivityManager(  907): Recipient 1361
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
E/AndroidRuntime( 5052): FATAL EXCEPTION: main
E/AndroidRuntime( 5052): Process: com.android.documentsui, PID: 5052
E/AndroidRuntime( 5052): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5052): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5052): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5052): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5052): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5052): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5052): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5052): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5052): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5052): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5052): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5052): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5052): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5052): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5052): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5052): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5052): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5052): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5052): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5052): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5052): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5052): 	... 10 more
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5065 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  907): Process com.google.process.gapps (pid 1361) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20828ms
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5077 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452010527273.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.j,ava:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
D/Process ( 5052): killProcess, pid=5052
D/Process ( 5052): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Recipient 5052
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.documentsui (pid 5052) has died.
D/ExternalStorage( 5065): After updating volumes, found 1 active roots
W/dalvikvm( 5077): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 5077): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5077): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5077): install
I/MultiDex( 5077): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 5077): loading existing secondary dex files
I/MultiDex( 5077): load found 3 secondary dex files

```
