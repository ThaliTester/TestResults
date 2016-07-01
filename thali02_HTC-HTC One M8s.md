#### Test 757892686fd65a6_thali02_HTC-HTC One M8s Logs


```
--------- beginning of main
07-01 08:58:18.048   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
--------- beginning of system
07-01 08:58:18.048  1339  1339 D WIFI_ICON: WifiActivity: 1
07-01 08:58:18.048   966   966 E WifiTrafficPoller:  packet count Tx=285 Rx=364
07-01 08:58:18.048  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-01 08:58:18.048   966   966 E WifiTrafficPoller: notifying of data activity 1
07-01 08:58:18.188   966  1259 E WifiStateMachine: handleMessage: E msg.what=131155
07-01 08:58:18.188   966  1259 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:18.188   966  1259 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=150 tx=0.1, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1522517038] gl hn u24 rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 08:58:18.188   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:18.188   966  1259 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2447 sc=60 link=150 tx=0.1, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1522517036] gl hn u24 rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 08:58:18.188   966  1259 E WifiStateMachine:  get link layer stats 0
07-01 08:58:18.188   966  1259 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-01 08:58:18.188  1428  1428 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
07-01 08:58:18.198  1428  1428 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-01 08:58:18.198   966  1259 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
07-01 08:58:18.198  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-01 08:58:18.198   966  1259 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
07-01 08:58:18.208  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-01 08:58:18.198   966  1259 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
07-01 08:58:18.198   966  1259 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.03 txretriesrate=0.00 rxrate=1.68 userTriggerdPenalty0
07-01 08:58:18.198   966  1259 E WifiStateMachine:  good link -> stuck count =0
07-01 08:58:18.198   966  1259 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-01 08:58:18.198   966  1259 E WifiStateMachine:  isHighRSSI       ---> score=61
07-01 08:58:18.198   966  1285 D WifiWatchdogStateMachine: RSSI current: 3 new: -53, 3
07-01 08:58:18.208   966  1259 E WifiStateMachine: handleMessage: X
,07-01 08:58:18.888  6867  6870 E cutils-trace: Error opening trace file: Permission denied (13)
07-01 08:58:18.938  6867  6867 D CustomizationManager: ====startRecUseTime====
07-01 08:58:18.938  6867  6867 D htc.customization.log.level:  is 
07-01 08:58:18.948  6867  6867 W CustomizationLogLevel: Level value is invalid, use default level 2
07-01 08:58:19.008  6867  6867 D CustomizationManager:  Read ACC file spent 0.037 (s)
07-01 08:58:19.008  6867  6867 D CIDMapFileReader: Parsing tag item name = HTC__001
07-01 08:58:19.008  6867  6867 D CIDMapFileReader: Parsing tag item name = HTC__102
07-01 08:58:19.008  6867  6867 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-01 08:58:19.008  6867  6867 D CIDMapFileReader: Parsing tag item name = HTC__032
07-01 08:58:19.008  6867  6867 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-01 08:58:19.008  6867  6867 D CIDMapFileReader: Parsing tag item name = HTC__002
07-01 08:58:19.008  6867  6867 D CIDMapFileReader: Parsing tag item name = HTC__031
07-01 08:58:19.008  6867  6867 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-01 08:58:19.008  6867  6867 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-01 08:58:19.008  6867  6867 I CustomizationCIDLoader: Parsing tag category name = system
07-01 08:58:19.008  6867  6867 I CustomizationCIDLoader: Parsing tag category name = application
07-01 08:58:19.008  6867  6867 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-01 08:58:19.008  6867  6867 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 08:58:19.008  6867  6867 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-01 08:58:19.008  6867  6867 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 08:58:19.008  6867  6867 I CustomizationCIDLoader: Parsing tag category name = ACC
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 42507
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 21902
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23420
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 22299
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 24002
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23210
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23205
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23806
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23430
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23408
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 27205
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-01 08:58:19.018  6867  6867 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-01 08:58:19.018  6867  6867 D CustomizationManager:  Read CID file spent 0.073 (s)
07-01 08:58:19.018  6867  6867 D CustomizationManager:  All configurations done spent 0.073 (s)
07-01 08:58:19.048   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-01 08:58:19.048  1339  1339 D WIFI_ICON: WifiActivity: 0
07-01 08:58:19.048   966   966 E WifiTrafficPoller:  packet count Tx=285 Rx=364
07-01 08:58:19.058  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-01 08:58:19.048   966   966 E WifiTrafficPoller: notifying of data activity 0
07-01 08:58:19.058   966  1830 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6867 on display 0
07-01 08:58:19.068   966  1082 D PMS     : acquireHCC(3a7da866): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 966 1000 null
07-01 08:58:19.068   966  1082 D PMS     : acquireHCC(15b3f7a7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 966 1000 null
07-01 08:58:19.078   966  1830 D PMS     : acquireWL(3551ffd): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 966 1000 null
07-01 08:58:19.088  1617  1617 I FeedHostManager: [onPause]
07-01 08:58:19.088  1617  1617 I FeedProviderManager: onPause
07-01 08:58:19.088  1617  1617 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@23a6cf6c
07-01 08:58:19.088  1617  2605 I SocialFeedProvider: +onPause
07-01 08:58:19.088  1617  2605 I SocialFeedProvider: -onPause
07-01 08:58:19.088  1617  1617 I ContextualWidget: onPause
07-01 08:58:19.088  1617  1617 I ContextualWidget: notifyWidgetDeactive
07-01 08:58:19.098   966  1049 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/10
07-01 08:58:19.108   966  1665 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-01 08:58:19.108   966  1648 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6884 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 08:58:19.128  1617  1617 I TrimMemoryManager: [trimMemory] 20
07-01 08:58:19.198   966  1047 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-01 08:58:19.198   966  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 08:58:19.198   966  1047 D StatusBarManagerService: hiding MENU key
07-01 08:58:19.278  6884  6884 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,07-01 08:58:19.328  6884  6884 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 6383-6392),
07-01 08:58:19.328  6884  6884 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 08:58:19.338  6884  6884 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37e513ce},
07-01 08:58:19.338  6884  6884 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 08:58:19.348  6884  6884 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,07-01 08:58:19.358  6884  6884 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-01 08:58:19.368  6884  6884 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,07-01 08:58:19.368  6884  6884 E SysUtils: ApplicationContext is null in ApplicationStatus,
,07-01 08:58:19.438  6884  6884 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,07-01 08:58:19.438  6884  6884 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
07-01 08:58:19.438  6884  6884 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 08:58:19.438  6884  6884 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-01 08:58:19.438  6884  6884 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-01 08:58:19.438  6884  6884 I Adreno-EGL: Build Date: 04/17/15 Fri
07-01 08:58:19.438  6884  6884 I Adreno-EGL: Local Branch: 
07-01 08:58:19.438  6884  6884 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-01 08:58:19.438  6884  6884 I Adreno-EGL: Local Patches: NONE
07-01 08:58:19.438  6884  6884 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-01 08:58:19.488   966  1048 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-01 08:58:19.488   966  1048 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bea5869:true
,07-01 08:58:19.488   966  1948 W System.err: java.lang.Throwable: stack dump
07-01 08:58:19.488   966  1948 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-01 08:58:19.488   966  1948 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
07-01 08:58:19.488   966  1948 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-01 08:58:19.488   966  1948 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,07-01 08:58:19.488  6884  6920 D BluetoothAdapter: 742563546: getState(). Returning 12,
,07-01 08:58:19.568  6884  6884 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,07-01 08:58:19.588  6884  6884 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 08:58:19.598  6884  6884 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,07-01 08:58:19.608  6884  6884 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 08:58:19.608  6884  6884 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 08:58:19.688  6884  6918 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,07-01 08:58:19.728  6884  6884 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,07-01 08:58:19.828  6884  6884 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@28eb2d56, mServedView=org.apache.cordova.engine.SystemWebView{3a76b1d7 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@32036ac4
,07-01 08:58:19.828   966  1884 I InputMethodManagerService: Disable input method client, pid=1617,
07-01 08:58:19.828   966  1884 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-01 08:58:19.828   966  1884 I InputMethodManagerService: Enable input method client, pid=6884
07-01 08:58:19.838  1339  1339 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-01 08:58:19.838   966  1049 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +749ms
,07-01 08:58:19.848   966  1492 D PMS     : releaseWL(3551ffd): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-01 08:58:19.878  1513  1513 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
07-01 08:58:19.878  1513  1513 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
07-01 08:58:19.878  1513  1513 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
07-01 08:58:19.878  1513  1513 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,07-01 08:58:19.938  6884  6884 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6884
,07-01 08:58:20.038  6884  6884 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 08:58:20.048   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
,07-01 08:58:20.048   966   966 E WifiTrafficPoller:  packet count Tx=285 Rx=364
,07-01 08:58:20.188  6884  6936 D jxcore_app_log: JniHelper::setJavaVM(0xab0cb7b8), pthread_self() = -1404959784
,07-01 08:58:20.198  6884  6936 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
07-01 08:58:20.198  6884  6936 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:20.198  6884  6936 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:20.198  6884  6936 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:20.198  6884  6936 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 08:58:20.198  6884  6936 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@564f448 added. We now have 1 listener(s)
,07-01 08:58:20.208   966  1270 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-01 08:58:20.208  6884  6936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
,07-01 08:58:20.208  6884  6936 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
07-01 08:58:20.208  6884  6936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 08:58:20.218  6884  6936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-01 08:58:20.218  6884  6936 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f1bec7 added. We now have 1 listener(s)
07-01 08:58:20.218  6884  6936 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 08:58:20.228   966  1260 D WifiService: New client listening to asynchronous messages
07-01 08:58:20.228   966   966 E WifiTrafficPoller: ADD_CLIENT: 8
,07-01 08:58:20.228  6884  6936 D BluetoothAdapter: 742563546: getState(). Returning 12,
07-01 08:58:20.228  6884  6936 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-01 08:58:20.238  6884  6936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 08:58:20.238  6884  6936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 08:58:20.238  6884  6936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 08:58:20.238  6884  6936 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 08:58:20.238  6884  6936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 08:58:20.238   966  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-01 08:58:20.238  6884  6936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,07-01 08:58:20.258  6884  6936 D BluetoothAdapter: 742563546: getState(). Returning 12
,07-01 08:58:20.258  6884  6936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:20.258  6884  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:20.258  6884  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-01 08:58:20.258  6884  6936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 08:58:20.258  6884  6936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 08:58:20.258  6884  6936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 08:58:20.258  6884  6936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 08:58:20.258  6884  6936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 08:58:20.258  6884  6936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 08:58:20.258  6884  6936 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 08:58:20.258  6884  6936 I io.jxcore.node.LifeCycleMonitor: start: OK,
,07-01 08:58:20.258  6884  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,07-01 08:58:20.258  6884  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 08:58:20.378  6884  6884 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 08:58:20.808  6884  6950 W jxcore-log: Initializing JXcore engine,
07-01 08:58:20.808  6884  6950 W jxcore-log: JXcore engine is ready
,07-01 08:58:20.858  6884  6950 W jxcore-log: Starting JXcore engine,
,07-01 08:58:20.958  6884  6950 W jxcore-log: Platform android,
07-01 08:58:20.958  6884  6950 W jxcore-log: 
07-01 08:58:20.958  6884  6950 W jxcore-log: Process ARCH arm
07-01 08:58:20.958  6884  6950 W jxcore-log: 
,07-01 08:58:21.048   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
,07-01 08:58:21.048   966   966 E WifiTrafficPoller:  packet count Tx=285 Rx=365
07-01 08:58:21.058  1339  1339 D WIFI_ICON: WifiActivity: 1
07-01 08:58:21.048   966   966 E WifiTrafficPoller: notifying of data activity 1
,07-01 08:58:21.058  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,07-01 08:58:21.068   966  1082 D PMS     : releaseHCC(3a7da866): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,07-01 08:58:21.068   966  1082 D PMS     : releaseHCC(15b3f7a7): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-01 08:58:21.158  6884  6950 I jxcore-log: JXcore Cordova bridge is ready!,
07-01 08:58:21.158  6884  6950 I jxcore-log: 
07-01 08:58:21.158  6884  6950 W jxcore-log: JXcore engine is started
,07-01 08:58:21.168  6884  6936 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 08:58:21.178  6884  6884 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 08:58:21.188  6884  6950 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-01 08:58:21.188  6884  6950 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 08:58:21.198  6884  6884 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
,07-01 08:58:21.198  6884  6884 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 08:58:21.208   966  1259 E WifiStateMachine: handleMessage: E msg.what=131155
07-01 08:58:21.208   966  1259 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:21.208   966  1259 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1522514015] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 08:58:21.208   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:21.208   966  1259 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1522514014] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 08:58:21.208   966  1259 E WifiStateMachine:  get link layer stats 0
07-01 08:58:21.208   966  1259 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-01 08:58:21.208  1428  1428 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-01 08:58:21.218  1428  1428 I wpa_supplicant: environment dirty rate=0 [0][0][0]
,07-01 08:58:21.218   966  1259 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
07-01 08:58:21.218   966  1259 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
07-01 08:58:21.218   966  1259 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
07-01 08:58:21.218   966  1259 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.02 txretriesrate=0.00 rxrate=1.34 userTriggerdPenalty0
07-01 08:58:21.218   966  1259 E WifiStateMachine:  good link -> stuck count =0
07-01 08:58:21.218   966  1259 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-01 08:58:21.218   966  1259 E WifiStateMachine:  isHighRSSI       ---> score=61
,07-01 08:58:21.238  6884  6884 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-01 08:58:21.238   966  1673 D PMS     : acquireWL(28d0bb13): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 966 1000 null
07-01 08:58:21.238  6884  6936 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 32ms. Plugin should use CordovaInterface.getThreadPool().
07-01 08:58:21.238  6884  6884 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-01 08:58:21.238   966  1259 E WifiStateMachine: handleMessage: X
07-01 08:58:21.238  1339  1339 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
,07-01 08:58:21.238   966  1285 D WifiWatchdogStateMachine: RSSI current: 3 new: -53, 3
07-01 08:58:21.238  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-01 08:58:21.238   966  1665 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,07-01 08:58:21.258  1617  1617 I FeedHostManager: [onResume]
07-01 08:58:21.258  1617  1617 I FeedProviderManager: onResume
07-01 08:58:21.268  1617  2605 I SocialFeedProvider: +onResume
07-01 08:58:21.268  1617  2605 I SocialFeedProvider: updateAccounts - Accounts is no change
07-01 08:58:21.268  1617  2605 I SocialFeedProvider: -onResume
,07-01 08:58:21.268  1617  1617 I ContextualWidget: onResume,
07-01 08:58:21.268  1617  1617 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
,07-01 08:58:21.268  1617  1919 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-01 08:58:21.268  1617  1617 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-01 08:58:21.268  1617  1617 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-01 08:58:21.268  1617  1617 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-01 08:58:21.268  1617  1617 I ContextualWidget: postSyncRecommendedApps, isReady=false allowAutoSync=true syncMode=1 isEnableRecommend=true,
,07-01 08:58:21.278   966  1047 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-01 08:58:21.278   966  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 08:58:21.278   966  1047 D StatusBarManagerService: hiding MENU key
,07-01 08:58:21.278  1617  1617 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-01 08:58:21.288  1617  1617 I ThreadedRenderer: Defer allocateBuffers to drawing time,
,07-01 08:58:21.288  1339  1339 I PhoneStatusBar: setImeWindowStatus(false,false),
07-01 08:58:21.288   966   989 I InputMethodManagerService: Disable input method client, pid=6884
07-01 08:58:21.288   966   989 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-01 08:58:21.298  6884  6884 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-01 08:58:21.288   966   989 I InputMethodManagerService: Enable input method client, pid=1617
,07-01 08:58:21.318   966  1673 D PMS     : releaseWL(28d0bb13): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-01 08:58:21.338   966  1047 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
07-01 08:58:21.338   966  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-01 08:58:21.338   966  1047 D StatusBarManagerService: hiding MENU key
,07-01 08:58:21.368   966  1022 I ActivityManager: Killing 6580:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
07-01 08:58:21.368   966  1022 D Process : killProcessQuiet, pid=6580
,07-01 08:58:21.368   966  1022 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityStack.destroyActivityLocked:3435 
,07-01 08:58:21.378   468   468 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-01 08:58:21.448   966   988 I ActivityManager: Recipient 6580
07-01 08:58:21.448   966  1260 D WifiService: Client connection lost with reason: 4
,07-01 08:58:21.478  6884  6884 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
07-01 08:58:21.478  6884  6884 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-01 08:58:21.478  6884  6884 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-01 08:58:21.478  6884  6884 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-01 08:58:21.478  6884  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-01 08:58:21.478  6884  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 08:58:21.478  6884  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 08:58:21.478  6884  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-01 08:58:21.478  6884  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@564f448 removed from the list
07-01 08:58:21.478  6884  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 08:58:21.488  6884  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f1bec7 removed from the list
07-01 08:58:21.488  6884  6884 D io.jxcore.node.ConnectivityMonitor: stop
07-01 08:58:21.488  6884  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-01 08:58:21.488  6884  6884 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 08:58:21.528  6951  6955 E cutils-trace: Error opening trace file: Permission denied (13)
,07-01 08:58:21.578  6951  6951 D CustomizationManager: ====startRecUseTime====,
07-01 08:58:21.578  6951  6951 D htc.customization.log.level:  is 
07-01 08:58:21.578  6951  6951 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-01 08:58:21.648  6951  6951 D CustomizationManager:  Read ACC file spent 0.036 (s)
,07-01 08:58:21.648  6951  6951 D CIDMapFileReader: Parsing tag item name = HTC__001
,07-01 08:58:21.648  6951  6951 D CIDMapFileReader: Parsing tag item name = HTC__102
07-01 08:58:21.648  6951  6951 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-01 08:58:21.648  6951  6951 D CIDMapFileReader: Parsing tag item name = HTC__032,
07-01 08:58:21.648  6951  6951 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-01 08:58:21.648  6951  6951 D CIDMapFileReader: Parsing tag item name = HTC__002
07-01 08:58:21.648  6951  6951 D CIDMapFileReader: Parsing tag item name = HTC__031
07-01 08:58:21.648  6951  6951 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-01 08:58:21.648  6951  6951 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
,07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: Parsing tag category name = system
,07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: Parsing tag category name = application
,07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
,07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 42507
,07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 21902
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23420
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 22299
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 24002
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23210
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23205
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23806
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23430
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23408
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 27205
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0,
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-01 08:58:21.658  6951  6951 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-01 08:58:21.658  6951  6951 D CustomizationManager:  Read CID file spent 0.080 (s)
07-01 08:58:21.658  6951  6951 D CustomizationManager:  All configurations done spent 0.080 (s)
07-01 08:58:21.698   966  1948 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=6951, uid=2000 userid=0
,07-01 08:58:21.708   966  1022 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg,
07-01 08:58:21.708   966  1022 I ActivityManager: Killing 6884:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest
07-01 08:58:21.708   966  1022 D Process : killProcessQuiet, pid=6884
,07-01 08:58:21.718   966  1022 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6372 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 ,
,07-01 08:58:21.738   966   966 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,07-01 08:58:21.738   966  6969 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=262 rxSum=251} preTxRxSum={txSum=262 rxSum=251}
,07-01 08:58:21.738   966  6969 D WifiDataStallTracker: updateDataStallInfo: NONE
07-01 08:58:21.738   966  6969 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-01 08:58:21.788   966  1173 W PackageSettings: Skipping PackageSetting{7b3c6d1 com.example.hello/10374} due to missing metadata
,07-01 08:58:21.808   966  1673 I ActivityManager: Recipient 6884
07-01 08:58:21.808   966  1260 D WifiService: Client connection lost with reason: 4
07-01 08:58:21.808  1513  1513 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1f6ad39e uid 10195 pid 6884} (c)'
,07-01 08:58:21.818  1617  2184 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-01 08:58:21.818   966  1022 W ActivityManager: ProcessRecord{10538e81 6884:com.test.thalitest/u0a195} has been replaced to new process null
,07-01 08:58:21.828   966  1673 W ActivityManager: Spurious death for ProcessRecord{10538e81 0:com.test.thalitest/u0a195}, curProc for 6884: null,
07-01 08:58:21.828   966  1173 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
,07-01 08:58:21.848  1429  1429 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-01 08:58:21.848  1429  1429 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,07-01 08:58:21.858   966  1492 D PMS     : acquireWL(21c52b26): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1852 10024 WorkSource{10024 com.google.android.gms}
,07-01 08:58:21.858  1852  2255 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-01 08:58:21.858   966  1251 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-01 08:58:21.858   966  1257 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
07-01 08:58:21.858   966  6515 D PMS     : releaseWL(21c52b26): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-01 08:58:21.858   966  1256 D PMS     : acquireWL(24a991bd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
07-01 08:58:21.868  1741  2089 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-01 08:58:21.878  1707  6970 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-01 08:58:21.878  1741  2089 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,07-01 08:58:21.888  1679  6971 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,07-01 08:58:21.898  6800  6800 I art     : Explicit concurrent mark sweep GC freed 449(29KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 528us total 60.768ms,
07-01 08:58:21.898  1679  6971 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-01 08:58:21.908   966  1256 D PMS     : releaseWL(24a991bd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-01 08:58:21.908   966  1257 V NetworkPolicy: writePolicyLocked()
,07-01 08:58:21.928   966  1257 V NetworkPolicy: updateNetworkEnabledLocked()
07-01 08:58:21.928   966  1257 V NetworkPolicy: updateNotificationsLocked()
07-01 08:58:21.928   966  1068 I PMS     : Going to sleep due to screen timeout (uid 1000)...
07-01 08:58:21.928   966  1074 D ActivityManager: getTaskThumbnailLocked mainThumbnail is null, TaskRecord{337fe80 #99 A=.Prism U=0 sz=1},
07-01 08:58:21.928  1617  1617 I art     : Explicit concurrent mark sweep GC freed 33373(2MB) AllocSpace objects, 29(871KB) LOS objects, 32% free, 32MB/48MB, paused 1.637ms total 103.180ms
07-01 08:58:21.928   966  1074 W PMS     : mWirelessDisplayManager is null
07-01 08:58:21.928   966  1074 W PMS     : mWirelessDisplayManager is still null
07-01 08:58:21.938  1617  1617 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
07-01 08:58:21.928   966  1021 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
07-01 08:58:21.938   966  1068 I PMS     : Sleeping (uid 1000)...
07-01 08:58:21.938   966  1068 D XAN-DPS : prepareColorFade 1
,07-01 08:58:21.938  1617  1617 I ContextualWidget: package com.test.thalitest removed
,07-01 08:58:21.948  1741  2089 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,07-01 08:58:21.948  1565  1565 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,07-01 08:58:21.958   966  6515 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6973 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
07-01 08:58:21.958   966  1068 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-01 08:58:21.958   966  1068 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-01 08:58:21.958   966  1068 I Adreno-EGL: Build Date: 04/17/15 Fri
07-01 08:58:21.958   966  1068 I Adreno-EGL: Local Branch: 
07-01 08:58:21.958   966  1068 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-01 08:58:21.958   966  1068 I Adreno-EGL: Local Patches: NONE
07-01 08:58:21.958   966  1068 I Adreno-EGL: Reconstruct Branch: NOTHING
07-01 08:58:21.968   966  1021 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-01 08:58:21.988  1741  2089 E ExternalAccountType: Unsupported attribute readOnly
,07-01 08:58:22.088   966   966 I art     : Explicit concurrent mark sweep GC freed 42807(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 18MB/28MB, paused 2.138ms total 246.601ms
,07-01 08:58:22.088   966  1173 I art     : WaitForGcToComplete blocked for 227.621ms for cause Explicit
,07-01 08:58:22.098  1617  1840 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
,07-01 08:58:22.098  1617  1840 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-01 08:58:22.118  1617  1919 I ContextualWidget: MFU.onDataSetChanged,
07-01 08:58:22.118  1617  1919 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-01 08:58:22.118  1617  1919 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
,07-01 08:58:22.138  6973  6973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 ,
,07-01 08:58:22.208  1617  1919 I ContextualWidget: MFU.onLoadComplete
07-01 08:58:22.208  1617  1919 W SystemReader: Cannot find enable_download_option, use default value instead
07-01 08:58:22.208  1617  1919 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-01 08:58:22.208  1617  1919 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-01 08:58:22.208  1617  1919 I ContextualWidget: sync all data, download=0 recommend=4
,07-01 08:58:22.208  1617  1919 I ContextualWidget: sync all data, mode=GettingOut count=1
07-01 08:58:22.208  1617  1919 I ContextualWidget: notifyDataChanged, list size 3
07-01 08:58:22.208  1906  1906 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-01 08:58:22.208  1906  1906 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-01 08:58:22.218   966  1648 D PMS     : acquireWL(103e2a37): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1906 10024 WorkSource{10024 com.google.android.gms}
,07-01 08:58:22.228   966  1249 D PMS     : acquireWL(38deeba4): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{1000}
07-01 08:58:22.228   966  1249 V AlarmManager: sending alarm PendingIntent{5d060c: PendingIntentRecord{38bb6b55 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1467356291836, Int=20000
,07-01 08:58:22.228   966  1804 D PMS     : releaseWL(103e2a37): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,07-01 08:58:22.238   966   966 W PackageManager: Unable to load service info ResolveInfo{19b20b3c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
07-01 08:58:22.238   966   966 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-01 08:58:22.238   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-01 08:58:22.238   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-01 08:58:22.238   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-01 08:58:22.238   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-01 08:58:22.238   966   966 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-01 08:58:22.238   966   966 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-01 08:58:22.238   966   966 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 08:58:22.238   966   966 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 08:58:22.238   966   966 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:22.238   966   966 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-01 08:58:22.238   966   966 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-01 08:58:22.238   966   966 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:22.238   966   966 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:22.238   966   966 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-01 08:58:22.238   966   966 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-01 08:58:22.258   966  1068 D XAN-DPS : prepareColorFade done
07-01 08:58:22.258   966  1068 D PMS     : MSG: UDAS true->false
07-01 08:58:22.258   966  1292 D XAN-DPS : setBrightness to 0
07-01 08:58:22.268  2225  7002 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-01 08:58:22.268  2225  2225 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-01 08:58:22.268  2225  2225 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-01 08:58:22.268  2225  7002 D AccountUtils: Clearing selected account for com.test.thalitest
07-01 08:58:22.278   966  1068 I SensorManager: unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1b7489b0
07-01 08:58:22.278   966  1068 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-01 08:58:22.278   966  1068 W SensorService: disable: get sensor name = Accelerometer Sensor
07-01 08:58:22.278  2225  2225 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-01 08:58:22.278  2225  2225 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-01 08:58:22.278   966  1068 W SensorService: pid=966, uid=1000
07-01 08:58:22.278   966  1068 W SensorService: Active sensors: size = 4
07-01 08:58:22.278   966  1068 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
07-01 08:58:22.278   966  1068 W SensorService: CM32181 Light sensor (handle=0x00000003, connections=1)
,07-01 08:58:22.278   966  1068 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
07-01 08:58:22.278   966  1068 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-01 08:58:22.278   966  1068 W SensorService: SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@1b7489b0, eanble = 0, strlen(mName) = 91
07-01 08:58:22.278   966  1049 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-01 08:58:22.278   966  1068 W SensorService: Active Listeners: mActiveListeners.size() = 2
07-01 08:58:22.278   966  1068 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@12a89dd0
07-01 08:58:22.278   966  1068 W SensorService: Listener[1] = com.htc.smartdim.sensor_eye@10dd5791
07-01 08:58:22.278   966  1068 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
07-01 08:58:22.288  1429  1429 D DotMatrix: [EventService]  onDisplayChanged: 0
07-01 08:58:22.288   966  1068 I SensorManager: unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@12a89dd0
07-01 08:58:22.288   966  1068 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-01 08:58:22.288   966  1068 W SensorService: disable: get sensor name = CM32181 Light sensor
07-01 08:58:22.288  1429  1429 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
07-01 08:58:22.288   388   388 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
07-01 08:58:22.288   388   388 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,07-01 08:58:22.288   966  1173 I art     : Explicit concurrent mark sweep GC freed 9545(624KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/28MB, paused 3.791ms total 205.844ms
07-01 08:58:22.288   966  1068 W SensorService: pid=966, uid=1000
07-01 08:58:22.288   966  1068 W SensorService: Active sensors: size = 3
07-01 08:58:22.288   966  1068 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
07-01 08:58:22.288   966  1068 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
07-01 08:58:22.288   966  1068 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-01 08:58:22.288   966  1068 W SensorService: SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@12a89dd0, eanble = 0, strlen(mName) = 67
07-01 08:58:22.288   966  1068 W SensorService: Active Listeners: mActiveListeners.size() = 1
07-01 08:58:22.288   966  1068 W SensorService: Listener[0] = com.htc.smartdim.sensor_eye@10dd5791
07-01 08:58:22.288   966  1068 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
07-01 08:58:22.288   966  1068 D XAN-DPC : mRamp.onAnimationEnd. policy=0
07-01 08:58:22.318  2225  7002 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-01 08:58:22.328   966  1648 D PMS     : acquireWL(39cf6a93): PARTIAL_WAKE_LOCK  AsyncService 0x1 6768 10167 null
,07-01 08:58:22.328   966  1492 D PMS     : releaseWL(39cf6a93): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,07-01 08:58:22.338   966  1882 D PMS     : acquireWL(36afb3e8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6768 10167 null
,07-01 08:58:22.358  2225  7007 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,07-01 08:58:22.358  2225  7007 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,07-01 08:58:22.358  2225  7007 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-01 08:58:22.358  2225  7007 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-01 08:58:22.368  6800  7011 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-01 08:58:22.368  2225  7007 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-01 08:58:22.368  2225  7007 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-01 08:58:22.368  2225  7007 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-01 08:58:22.378  2225  7007 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-01 08:58:22.378  2225  7007 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,07-01 08:58:22.388  2225  7007 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-01 08:58:22.388  2225  7007 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
07-01 08:58:22.388  2225  7007 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
07-01 08:58:22.388  2225  7007 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
07-01 08:58:22.388   966   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.GetContentActivityAlias, state=2, flag=1, pid=6768, uid=10167, userID:0
07-01 08:58:22.388   966  1648 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SendContentActivityAlias, state=2, flag=1, pid=6768, uid=10167, userID:0
,07-01 08:58:22.388   966  1884 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.phone.SetWallpaperActivityAlias, state=2, flag=1, pid=6768, uid=10167, userID:0
07-01 08:58:22.388   966   966 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-01 08:58:22.388   966  2384 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.VideoViewActivityAlias, state=2, flag=1, pid=6768, uid=10167, userID:0
,07-01 08:58:22.388  6660  6660 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest],
07-01 08:58:22.388   966  1948 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias, state=2, flag=1, pid=6768, uid=10167, userID:0
07-01 08:58:22.398  6660  6660 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
07-01 08:58:22.398   966  1673 D PMS     : releaseWL(295a80d7): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
07-01 08:58:22.398   966  1673 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.plus.service.EsDreamService, state=2, flag=1, pid=6768, uid=10167, userID:0
07-01 08:58:22.398   966   988 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestActivity, state=2, flag=1, pid=6768, uid=10167, userID:0
,07-01 08:58:22.398   966  1648 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.libraries.social.ingest.IngestService, state=2, flag=1, pid=6768, uid=10167, userID:0
,07-01 08:58:22.398   966  1729 D PMS     : acquireWL(14941fdf): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 2225 10024 null
,07-01 08:58:22.398   966   966 W PMN     : goingToSleep
,07-01 08:58:22.408   966  2384 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.photos.service.GooglePhotoDownsyncService, state=2, flag=1, pid=6768, uid=10167, userID:0
,07-01 08:58:22.408  1339  1362 W HtcLockScreen: KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-01 08:58:22.408   966  1804 D PMS     : releaseWL(36afb3e8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
07-01 08:58:22.408  1906  1906 I ConfigService: onCreate
07-01 08:58:22.408  2225  2225 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-01 08:58:22.408   966   988 D PMS     : releaseWL(14941fdf): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,07-01 08:58:22.408   966   966 D PMS     : acquireWL(144dafb): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 966 1000 null
07-01 08:58:22.408   966   966 W PMN     : goingToSleep done
,07-01 08:58:22.418  6660  6660 I DeviceManagement: WorkflowService: Starting workflow service
,07-01 08:58:22.418  6660  7013 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@2c429eda] args=[Bundle[mParcelledData.dataSize=112]]
07-01 08:58:22.418  6660  7013 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-01 08:58:22.418  6660  7013 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,07-01 08:58:22.418  6660  7013 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-01 08:58:22.418  1339  1339 D BlindfeedViewCtrl: onScreenTurnedOff
,07-01 08:58:22.428  6660  7013 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,07-01 08:58:22.428   966  1477 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7015 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a,
,07-01 08:58:22.448  1617  1617 I FeedHostManager: [onPause]
07-01 08:58:22.448   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
07-01 08:58:22.448   966   966 E WifiTrafficPoller:  packet count Tx=285 Rx=365
07-01 08:58:22.448   966   966 V ActivityManager: Display changed displayId=0
07-01 08:58:22.448   966   966 E WifiTrafficPoller: notifying of data activity 0
07-01 08:58:22.448  1339  1339 D WIFI_ICON: WifiActivity: 0
,07-01 08:58:22.448  1339  1339 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-01 08:58:22.448  1617  1617 I FeedProviderManager: onPause
07-01 08:58:22.448  1617  1617 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@23a6cf6c
07-01 08:58:22.448  1617  2605 I SocialFeedProvider: +onPause
07-01 08:58:22.448  1617  2605 I SocialFeedProvider: -onPause
07-01 08:58:22.448  1617  1617 I ContextualWidget: onPause
07-01 08:58:22.448  1617  1617 I ContextualWidget: notifyWidgetDeactive
,07-01 08:58:22.458   966   966 D AlarmManager: ACTION_SCREEN_ON
,07-01 08:58:22.458   966   966 I AlarmManager: [AlarmQueuing] recover blocked alarms
07-01 08:58:22.458   966   966 I AlarmManager: [AlarmQueuing] done recovering
07-01 08:58:22.458   966   966 I AlarmManager: [AlarmQueuing] recover EPS screen off blocked alarms
07-01 08:58:22.458   966   966 I AlarmManager: [AlarmQueuing] done EPS screen off alarm recovering,
,07-01 08:58:22.458  2225  7032 I PeopleContactsSync: CP2 sync disabled
07-01 08:58:22.458  6660  7013 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
07-01 08:58:22.458   966  1665 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-01 08:58:22.468   966   966 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL true Token 11
07-01 08:58:22.468   966   966 E WifiTrafficPoller:  packet count Tx=285 Rx=365
07-01 08:58:22.468  6660  7037 I DeviceManagement: SessionStateController: Checking invariants...
07-01 08:58:22.468   966   989 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2225, uid=10024, userID:0
07-01 08:58:22.468   966   966 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL true Token 1
07-01 08:58:22.468   966  1477 D PMS     : releaseWL(144dafb): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
07-01 08:58:22.468   966  1259 E WifiStateMachine: handleMessage: E msg.what=131167
07-01 08:58:22.468   966  1259 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:22.468   966  1259 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
07-01 08:58:22.468   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:22.478   966  1259 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
07-01 08:58:22.478   966  1259 E WifiStateMachine: processMsg: ConnectModeState
07-01 08:58:22.478   966  1259 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
07-01 08:58:22.478   966  1259 E WifiStateMachine: processMsg: DriverStartedState
07-01 08:58:22.478   966  1259 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-01 08:58:22.478   966  1259 D WifiDisplayAdapter:     Client/Owner: Client
07-01 08:58:22.478   966  1259 D WifiDisplayAdapter:     GroupId: 
07-01 08:58:22.478   966  1259 D WifiDisplayAdapter:     Passphrase: 
07-01 08:58:22.478   966  1259 D WifiDisplayAdapter:     SessionId: 0
07-01 08:58:22.478   966  1259 D WifiDisplayAdapter:     IP Address: }
07-01 08:58:22.478   966  1259 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
07-01 08:58:22.478   966  1259 E WifiStateMachine: processMsg: SupplicantStartedState
07-01 08:58:22.478   966  1259 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
07-01 08:58:22.478   966  1259 E WifiStateMachine: processMsg: DefaultState
07-01 08:58:22.478   966  1259 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
07-01 08:58:22.478   966  1259 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
07-01 08:58:22.478   966  1259 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
07-01 08:58:22.478  1428  1428 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 1'
07-01 08:58:22.478  1428  1428 I wpa_supplicant: SET_SCREEN_ON:On
07-01 08:58:22.478  1428  1428 I wpa_supplicant: htc_wext_set_keepalive +
07-01 08:58:22.478  1428  1428 I wpa_supplicant: htc_wext_set_keepalive: enable=0, type=2, interval=15
07-01 08:58:22.478  1428  1428 D wpa_supplicant: getPrivFuncNum +	
07-01 08:58:22.478  1428  1428 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
07-01 08:58:22.478  1428  1428 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
07-01 08:58:22.478  1428  1428 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
07-01 08:58:22.478  1428  1428 I wpa_supplicant: htc_wext_set_TX_TRACKING (1)+
07-01 08:58:22.478  1428  1428 I wpa_supplicant: htc_wext_set_TX_TRACKING - ret = 0
07-01 08:58:22.478   966  1259 E WifiStateMachine: setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
07-01 08:58:22.478   966  ,1259 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
07-01 08:58:22.478   966  1259 E WifiStateMachine: handleScreenStateChanged Exit: true
07-01 08:58:22.478   966  1259 E WifiStateMachine: handleMessage: X
07-01 08:58:22.478   966  1259 E WifiStateMachine: handleMessage: E msg.what=131154
07-01 08:58:22.478   966  1259 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:22.478   966  1259 E WifiStateMachine:  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-01 08:58:22.478   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:22.478   966  1259 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
07-01 08:58:22.478   438   438 V SRS_Proc: ParamSet string: screen_state=on
07-01 08:58:22.478   966  1259 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-01 08:58:22.478  1428  1428 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
07-01 08:58:22.488   966  1673 D PMS     : acquireWL(353767ad): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10024 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.478   438   438 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-01 08:58:22.478   966  1260 D WifiController: handleMessage: E msg.what=155650
07-01 08:58:22.478   966  1260 D WifiController: processMsg: DeviceActiveState
07-01 08:58:22.478   966  1260 D WifiController: processMsg: StaEnabledState
07-01 08:58:22.478   966  1260 D WifiController: processMsg: DefaultState
07-01 08:58:22.478   966  1260 D WifiController: handleMessage: X
07-01 08:58:22.488   966  7040 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=262 rxSum=251} preTxRxSum={txSum=262 rxSum=251}
07-01 08:58:22.488   966  1257 D NetworkPolicy: updateScreenOn: false
07-01 08:58:22.488   966  7040 D WifiDataStallTracker: updateDataStallInfo: NONE
07-01 08:58:22.488   966  1257 V NetworkPolicy: updateIfacesLocked()
07-01 08:58:22.488   966  7040 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
07-01 08:58:22.488   966  1257 D NetworkManagementService: isBandwidthControlEnabled: doneSignal.getCount()= 0
07-01 08:58:22.488   966  1021 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-01 08:58:22.488  2225  4990 I Icing   : doRemovePackageData com.test.thalitest
07-01 08:58:22.488  1428  1428 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-01 08:58:22.488   966  1259 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 150
07-01 08:58:22.488   966  1259 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-52 linkspeed=150
07-01 08:58:22.488   966  1259 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
07-01 08:58:22.488   966  1259 E WifiStateMachine: handleMessage: X
07-01 08:58:22.488   966  1259 E WifiStateMachine: handleMessage: E msg.what=131127
07-01 08:58:22.488   966  1259 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:22.488   966  1259 E WifiStateMachine:  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-01 08:58:22.488   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:22.488   966  1259 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
07-01 08:58:22.488   966  1259 E WifiStateMachine: processMsg: ConnectModeState
07-01 08:58:22.498   966  1259 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
07-01 08:58:22.498   966  1259 E WifiStateMachine: handleMessage: X
07-01 08:58:22.498   966  1259 E WifiStateMachine: handleMessage: E msg.what=131129
07-01 08:58:22.498   966  1259 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:22.498   966  1259 E WifiStateMachine:  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-01 08:58:22.498   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:22.498   966  1259 E WifiStateMachine:  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
07-01 08:58:22.498   966  1259 E WifiStateMachine: processMsg: ConnectModeState
07-01 08:58:22.498   966  1259 E WifiStateMachine:  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
07-01 08:58:22.498   966  1259 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
07-01 08:58:22.498  1428  1428 D wpa_supplicant: wlan0: Control interface command 'BLACKLIST clear'
07-01 08:58:22.498  1428  1428 E wpa_supplicant: wlan0: BLACKLIST CLEAR 
07-01 08:58:22.498   966  1623 D WifiMonitor: Event [IFNAME=wlan0 BLACKLIST CLEAR ]
07-01 08:58:22.498   966  1623 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: BLACKLIST CLEAR 
07-01 08:58:22.498   966  1259 E WifiStateMachine: handleMessage: X
07-01 08:58:22.498   966  1269 D PMS     : releaseWL(353767ad): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.498  1429  1429 D DotMatrix: [EventService] mHtcSpeakerReceiver.onReceive, action: android.intent.action.SCREEN_ON, mCoverOn = false
07-01 08:58:22.498  1429  1429 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,mbIsUserInForeground:true
07-01 08:58:22.498  1429  1429 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,mbIsUserInForeground:true
07-01 08:58:22.518  1339  1693 I IntentController: receive(android.intent.action.SCREEN_ON,1,false)
07-01 08:58:22.518   966  1948 D PMS     : acquireWL(13d3f32e): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10024 WorkSource{10024 com.google.android.gms}
,07-01 08:58:22.518   966  1477 D PMS     : acquireWL(8eabecf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1852 10024 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.518  2225  7009 W BaseAppContext: Using Auth Proxy for data requests.
07-01 08:58:22.528   966  1830 D PMS     : releaseWL(13d3f32e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.528   966  1492 D PMS     : acquireWL(3530805c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1852 10024 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.528   966  1830 D PMS     : releaseWL(8eabecf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.538   966  2384 D PMS     : acquireWL(430143a): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10024 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.538  2225  7009 W BaseAppContext: Using Auth Proxy for data requests.
07-01 08:58:22.538   966  1729 D PMS     : releaseWL(3530805c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.548   966  1294 D TaskPersister: removeObsoleteFile: deleting file=100_task.xml
07-01 08:58:22.548   966  1294 D TaskPersister: removeObsoleteFile: deleting file=100_task_thumbnail.png
,07-01 08:58:22.568   966   966 D AlarmManager: ACTION_SCREEN_OFF
,07-01 08:58:22.568   966   966 I AlarmManager: [AlarmQueuing] screen off now: 
07-01 08:58:22.568   966   966 I AlarmManager: [AlarmQueuing] data connection: true
07-01 08:58:22.568   966   966 I AlarmManager: [AlarmQueuing] wifi connection: true
07-01 08:58:22.568   966   966 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 12
,07-01 08:58:22.568   966   966 D WifiDataStallTracker: stopDataStallAlarm 
07-01 08:58:22.568   966   966 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL false Token 2
07-01 08:58:22.568   966  1259 E WifiStateMachine: handleMessage: E msg.what=131167
07-01 08:58:22.568   966  1259 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:22.568   966  1259 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
07-01 08:58:22.568   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:22.568   966  1259 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
,07-01 08:58:22.568   966  1259 E WifiStateMachine: processMsg: ConnectModeState
07-01 08:58:22.578   388   670 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
07-01 08:58:22.578   966  1292 D PMS     : Setting HAL interactive mode to false
07-01 08:58:22.578   388   670 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
07-01 08:58:22.578   966  1292 D PMS     : Setting HAL interactive mode to false done
07-01 08:58:22.578  1339  1339 I SensorManager: registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@3f77a88a, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
07-01 08:58:22.578   966  1292 D PMS     : Setting HAL auto-suspend mode to true
07-01 08:58:22.578   438  1034 V SRS_Proc: ParamSet string: screen_state=off
07-01 08:58:22.578   966  1292 D PMS     : Setting HAL auto-suspend mode done
07-01 08:58:22.578   438  1034 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-01 08:58:22.578   966  1259 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-01 08:58:22.578   966  1259 D WifiDisplayAdapter:     Client/Owner: Client
07-01 08:58:22.578   966  1259 D WifiDisplayAdapter:     GroupId: 
07-01 08:58:22.578   966  1259 D WifiDisplayAdapter:     Passphrase: 
07-01 08:58:22.578   966  1259 D WifiDisplayAdapter:     SessionId: 0
07-01 08:58:22.578   966  1259 D WifiDisplayAdapter:     IP Address: }
07-01 08:58:22.578   966  1259 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
07-01 08:58:22.578   966  1259 E WifiStateMachine: processMsg: DriverStartedState
07-01 08:58:22.578   966  1292 D SurfaceControl: Excessive delay in setPowerMode(): 298ms
07-01 08:58:22.578   966  1259 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-01 08:58:22.578   966  1259 E WifiStateMachine: processMsg: SupplicantStartedState
07-01 08:58:22.578   966  1259 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
07-01 08:58:22.578   966  1259 E WifiStateMachine: processMsg: DefaultState
07-01 08:58:22.578   966  1259 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
07-01 08:58:22.578   966  1259 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
07-01 08:58:22.578   966  1259 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
07-01 08:58:22.578  1428  1428 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 0'
07-01 08:58:22.578  1428  1428 I wpa_supplicant: SET_SCREEN_ON:Off
07-01 08:58:22.578  1428  1428 I wpa_supplicant: htc_wext_set_keepalive +
07-01 08:58:22.578  1428  1428 I wpa_supplicant: htc_wext_set_keepalive: enable=1, type=2, interval=15
07-01 08:58:22.578  1428  1428 D wpa_supplicant: getPrivFuncNum +	
07-01 08:58:22.578  1428  1428 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
07-01 08:58:22.578  1428  1428 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
07-01 08:58:22.578  1428  1428 I wpa_supplicant: get_ip_address source addr = c0a8016b
07-01 08:58:22.578  1428  1428 I wpa_supplicant: htc_wext_set_keepalive gateway addr = c0a80101
07-01 08:58:22.578  1428  1428 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
07-01 08:58:22.578   966  1259 E WifiStateMachine: setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
07-01 08:58:22.578   966  1259 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
07-01 08:58:22.578   966  1259 E WifiStateMachine: handleScreenStateChanged Exit: false
07-01 08:58:22.578   966  1259 E WifiStateMachine: handleMessage: X
07-01 08:58:22.578   966  1259 E WifiStateMachine: handleMessage: E msg.what=131154
07-01 08:58:,22.578   966  1259 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:22.578   966  1259 E WifiStateMachine:  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-01 08:58:22.578   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:22.578   966  1259 E WifiStateMachine:  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
07-01 08:58:22.578   966  1259 E WifiStateMachine: handleMessage: X
07-01 08:58:22.578   966  1729 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-01 08:58:22.578   966  1729 W SensorService: enable: get sensor name = hTC Gesture Motion HIDI
,07-01 08:58:22.588   966  1729 W SensorService: pid=1339, uid=10041
07-01 08:58:22.588   966  1729 W SensorService: Active sensors: size = 4
07-01 08:58:22.588   966  1729 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
,07-01 08:58:22.588   966  1729 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
07-01 08:58:22.588   966  1729 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-01 08:58:22.588   966  1729 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
07-01 08:58:22.588   966  1804 W SensorService: SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@3f77a88a, eanble = 1, strlen(mName) = 57
07-01 08:58:22.588   966  1804 W SensorService: Active Listeners: mActiveListeners.size() = 2
07-01 08:58:22.588   966  1804 W SensorService: Listener[0] = com.htc.smartdim.sensor_eye@10dd5791
07-01 08:58:22.588   966  1804 W SensorService: Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@3f77a88a
07-01 08:58:22.588   966  1804 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
07-01 08:58:22.588   966   988 D PMS     : acquireWL(1d9f1a63): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
,07-01 08:58:22.588   966   988 I BatteryService: n_update end
07-01 08:58:22.588   966   988 D PMS     : releaseWL(1d9f1a63): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-01 08:58:22.598   966  2384 D PMS     : releaseWL(430143a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,07-01 08:58:22.608   966  1830 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7046 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a
,07-01 08:58:22.608   966  1665 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
07-01 08:58:22.608   966  1292 D HABCtrl : TPE algorithm. remove timeout.
07-01 08:58:22.608   966  1292 D PMS     : OOBE c monitor 11
07-01 08:58:22.608   966  1035 I InputMethodManagerService: screenObserver, isScreenOn=false
07-01 08:58:22.608  1587  1749 D NfcService: ScreenObserver: OFF
07-01 08:58:22.608   966  1035 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-01 08:58:22.608   966  1035 I InputMethodManagerService: Disable input method client, pid=1617
,07-01 08:58:22.608   966  1068 D HtcPowerSaver: updateBatteryInfo,
07-01 08:58:22.608  1587  7059 D NfcService: applyRouting - 0
07-01 08:58:22.608   966  1729 D PMS     : acquireWL(28a37719): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1587 1027 null
07-01 08:58:22.618  1429  1429 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-01 08:58:22.618  1429  1429 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-01 08:58:22.618  1429  1429 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-01 08:58:22.618   966  1260 D WifiController: handleMessage: E msg.what=155651
07-01 08:58:22.618   966  1260 D WifiController: processMsg: DeviceActiveState
07-01 08:58:22.618   966  1673 D PMS     : releaseWL(28a37719): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,07-01 08:58:22.618   966  1260 D WifiController: processMsg: StaEnabledState
07-01 08:58:22.618   966  1260 D WifiController: processMsg: DefaultState
07-01 08:58:22.618  3562  3650 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 08:58:22.618   966  1260 D WifiController: handleMessage: X
07-01 08:58:22.618  1587  7059 D NfcService: applyRouting -2
07-01 08:58:22.618  1587  7059 D NfcService: applyRouting
07-01 08:58:22.618  1587  7059 D NfcService: Ignore this applyRouting...
,07-01 08:58:22.628  1339  1693 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
07-01 08:58:22.628  6660  7037 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,07-01 08:58:22.638   966  2384 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7067 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-01 08:58:22.638   966  1884 D PMS     : acquireWL(29eb6bd5): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10024 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.638   966   966 D NotificationService: plugged=true pluggin=true
07-01 08:58:22.638   966   966 D UsbnetService: BroadcastReceiver::onReceive+
07-01 08:58:22.638   966   966 D PMS     : runPSCheck
07-01 08:58:22.638   966   966 D UsbnetService: onReceive BATTERY_CHANGED
07-01 08:58:22.638   966   966 D HtcPowerSaver: Checking...
,07-01 08:58:22.638   966   966 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,07-01 08:58:22.638   966   966 I HtcPowerSaver: >> updateStatus
07-01 08:58:22.638   966   966 D UsbnetService: BroadcastReceiver::onReceive-
07-01 08:58:22.638   966  1260 D WifiController: battery changed pluggedType: 2
07-01 08:58:22.638   966  1260 D WifiController: handleMessage: E msg.what=155652
,07-01 08:58:22.638   966  1260 D WifiController: processMsg: DeviceActiveState
07-01 08:58:22.638   966  1260 D WifiController: processMsg: StaEnabledState
07-01 08:58:22.638   966  1260 D WifiController: processMsg: DefaultState
07-01 08:58:22.638   966  1260 D WifiController: handleMessage: X
07-01 08:58:22.648  6800  7011 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 274 ms] updated apps [took 274 ms] 
,07-01 08:58:22.648   966   966 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-01 08:58:22.648   966   966 I HtcPowerSaver: << updateStatus
,07-01 08:58:22.648  1339  1339 D PowerUI : closing low battery warning: level=100
,07-01 08:58:22.658  1339  1339 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,07-01 08:58:22.658  1339  1339 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-01 08:58:22.658   966  1021 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-01 08:58:22.658   966  1257 D NetworkPolicy: updateScreenOn: false
07-01 08:58:22.658   966  1257 V NetworkPolicy: updateIfacesLocked()
,07-01 08:58:22.658   966  1257 D NetworkManagementService: isBandwidthControlEnabled: doneSignal.getCount()= 0
,07-01 08:58:22.658  1429  1429 D DotMatrix: [EventService] mHtcSpeakerReceiver.onReceive, action: android.intent.action.SCREEN_OFF, mCoverOn = false
,07-01 08:58:22.658  1429  1429 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
07-01 08:58:22.658  1429  1429 D DotMatrix: [EventService] getTotalRam: 1842 Mb
07-01 08:58:22.668  1565  7090 D ContactMessageStore: start background delete task...
07-01 08:58:22.668  1565  7090 D ContactMessageStore: size: 0 , 0
07-01 08:58:22.668  1565  7090 D ContactMessageStore: Background delete complete
,07-01 08:58:22.678  1339  1339 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-01 08:58:22.738  1339  1693 I IntentController: receive(android.intent.action.SCREEN_OFF,1,false)
,07-01 08:58:22.738  6660  7013 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,07-01 08:58:22.738  6660  7013 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@2c429eda],
07-01 08:58:22.738  1617  1617 I ContextualWidget: unlockModeChange
,07-01 08:58:22.748  7046  7046 D ExternalStorage: After updating volumes, found 1 active roots,
07-01 08:58:22.748  6660  6660 I DeviceManagement: WorkflowService: Stopping workflow service
07-01 08:58:22.748   966  6515 D PMS     : acquireWL(3683f051): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1852 10024 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.748   966  1882 D PMS     : releaseWL(3683f051): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-01 08:58:22.748   966  1270 D PMS     : acquireWL(190c30b6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1852 10024 WorkSource{10024 com.google.android.gms}
,07-01 08:58:22.758   966  1648 D Process : killProcessQuiet, pid=6307
,07-01 08:58:22.758   966  1648 I ActivityManager: Killing 6307:com.google.android.gm/u0a106 (adj 15): empty #17
,07-01 08:58:22.758   966  1648 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-01 08:58:22.788  1565  1736 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
,07-01 08:58:22.788  1565  1736 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,07-01 08:58:22.838   966  2384 I ActivityManager: Recipient 6307
,07-01 08:58:22.878   966  1882 D PMS     : releaseWL(190c30b6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,07-01 08:58:22.878  7067  7067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,07-01 08:58:22.898  7067  7096 D PowerUtils: getUserIdOfProcess, curUserId = 0
,07-01 08:58:22.898  7067  7096 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-01 08:58:22.908   966  1270 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7097 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,07-01 08:58:22.918  7067  7096 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
,07-01 08:58:22.928  7067  7096 D PowerUsageService: removed uid = 10195
,07-01 08:58:22.928   966   966 I InputManager: Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,07-01 08:58:22.928  1339  1693 I IntentController: receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false),
,07-01 08:58:22.938  7067  7096 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.,
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:389)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2149)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:106)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:22.938  7067  7096 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
07-01 08:58:22.938  7067  7096 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 7067
07-01 08:58:22.938  7067  7096 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.S,QLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:389)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2149)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:106)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:22.938  7067  7096 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:22.948   966  1492 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
,07-01 08:58:22.948   966  1492 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 08:58:22.948  6728  6728 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-01 08:58:22.948  6728  6728 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 08:58:22.948   966  1665 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 08:58:22.948   966  1665 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,07-01 08:58:22.948   966  1665 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:22.948   966  1665 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:22.948   966  1665 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:22.948   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 08:58:22.948   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 08:58:22.948   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 08:58:22.948   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 08:58:22.948   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 08:58:22.958   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 08:58:22.958   966  1665 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 08:58:22.958   966  1665 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:22.958   966  1665 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:22.958   966  1665 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:22.958   966  1665 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:22.958   966  1665 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:22.958   966  1665 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:22.958   966  1665 W System.err: 	... 12 more
07-01 08:58:22.958  7097  7097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 08:58:22.958   966  1492 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,07-01 08:58:22.958   966  1492 W System.err: ,	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:22.958   966  1492 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:22.958   966  1492 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:22.958   966  1492 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:22.958   966  1492 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
07-01 08:58:22.958   966  1492 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
07-01 08:58:22.958   966  1492 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
,07-01 08:58:22.958   966  1492 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:307)
07-01 08:58:22.958   966  1492 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:22.958   966  1492 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12583)
07-01 08:58:22.958   966  1492 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12247)
07-01 08:58:22.958   966  1492 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12219)
07-01 08:58:22.958   966  1492 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
07-01 08:58:22.958   966  1492 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
07-01 08:58:22.958   966  1492 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:22.958   966  1492 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,07-01 08:58:22.968   966  1492 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:22.968   966  1492 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:22.968   966  1492 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:22.968   966  1492 W System.err: 	... 14 more
,07-01 08:58:22.968   966  1492 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
07-01 08:58:22.968   966  1492 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:22.968   966  1492 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:22.978   966  1492 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,07-01 08:58:22.978   966  1492 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:22.978   966  1492 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
07-01 08:58:22.978   966  1492 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
07-01 08:58:22.978   966  1492 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
07-01 08:58:22.978   966  1492 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:308)
07-01 08:58:22.978   966  1492 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:22.978   966  1492 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12583)
07-01 08:58:22.978   966  1492 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12247),
07-01 08:58:22.978   966  1492 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12219)
07-01 08:58:22.978   966  1492 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
07-01 08:58:22.978   966  1492 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
07-01 08:58:22.978   966  1492 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:22.978   966  1492 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:22.978   966  1492 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:22.978   966  1492 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:22.978   966  1492 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:22.978   966  1492 W System.err: 	... 14 more
,07-01 08:58:22.978  1339  1339 I ClockController: stop clock update:screen off,
07-01 08:58:22.978   966  7118 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 08:58:22.978   966  7118 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467356302991.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 08:58:22.978   966  7118 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:22.978   966  7118 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:22.978   966  7118 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:22.978   966  7118 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:463)
07-01 08:58:22.978   966  7118 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:22.978   966  7118 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system),
07-01 08:58:22.978   966  7118 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:22.978   966  7118 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:22.978   966  7118 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:22.978   966  7118 E ErrorReport: 	... 4 more
,07-01 08:58:22.988  7067  7096 D Process : killProcess, pid=7067,
07-01 08:58:22.988   966   966 E WifiStateMachine: WiFiStateMachine SCAN ALARM
07-01 08:58:22.988   966   966 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-01 08:58:22.988   966   966 D WifiDisplayAdapter:     Client/Owner: Client
07-01 08:58:22.988   966   966 D WifiDisplayAdapter:     GroupId: 
07-01 08:58:22.988   966   966 D WifiDisplayAdapter:     Passphrase: 
07-01 08:58:22.988   966   966 D WifiDisplayAdapter:     SessionId: 0
07-01 08:58:22.988   966   966 D WifiDisplayAdapter:     IP Address: }
07-01 08:58:22.988   966  1259 E WifiStateMachine: handleMessage: E msg.what=131143,
07-01 08:58:22.988   966  1259 E WifiStateMachine: processMsg: ConnectedState
,07-01 08:58:22.988   966  1259 E WifiStateMachine:  ConnectedState CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:86 rssi=-52 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 list=2447 [on:0 tx:0 rx:0 period:1752] from screen [on:0 period:-1522512232]
,07-01 08:58:22.988   966  1259 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:22.988   966  1259 E WifiStateMachine:  L2ConnectedState CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:86 rssi=-52 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 list=2447 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1522512231]
07-01 08:58:22.988   966  1259 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-52
07-01 08:58:22.988   966  1259 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=40951 interval=40000 maxinterval=300000
07-01 08:58:22.988   966  1259 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=40951 interval=40000 maxinterval=300000
07-01 08:58:22.988   966  1259 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
07-01 08:58:22.988   966  1259 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =60000
07-01 08:58:22.988   966  1259 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
07-01 08:58:22.988  1428  1428 I wpa_supplicant: wpa_supplicant_scan enter
,07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS: Building WPS IE for Probe Request
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Request Type
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Config Methods (4288)
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * UUID-E
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Primary Device Type
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * RF Bands (3)
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Association State
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Configuration Error (0)
,07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Device Password ID (0)
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Manufacturer
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Model Name
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Model Number
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Device Name
07-01 08:58:22.988  1428  1428 D wpa_supplicant: WPS:  * Version2 (0x20)
07-01 08:58:22.988  1428  1428 D wpa_supplicant: P2P: * P2P IE header
07-01 08:58:22.988  1428  1428 D wpa_supplicant: P2P: * Capability dev=25 group=00
07-01 08:58:22.988  1428  1428 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: Add radio work 'scan'@0x559e675860
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x559e675860 after 0.000045 second wait
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: nl80211: scan request
07-01 08:58:22.988  1428  1428 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-01 08:58:22.988  1428  1428 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: nl80211: Scan trigger
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
07-01 08:58:22.988  1428  1428 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000103 seconds
,07-01 08:58:22.988  1428  1428 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-01 08:58:22.988   966  1623 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-01 08:58:22.988   966  1623 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-01 08:58:22.988   966  1623 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-01 08:58:22.988   966  1623 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-01 08:58:22.988   966  1259 E WifiStateMachine: [1,467,356,303,003 ms] noteScanstart no scan source
07-01 08:58:22.988  7067  7096 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 08:58:22.988   966  1259 E WifiStateMachine: handleMessage: X
,07-01 08:58:22.998  7015  7041 D Documents: Update found 7 roots in 458ms
,07-01 08:58:23.008   966   966 I ActivityManager: Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=7120 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
07-01 08:58:23.008   966   966 D PMS     : releaseWL(38deeba4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,07-01 08:58:23.018  7015  7095 D Documents: Update found 7 roots in 262ms
,07-01 08:58:23.028  7097  7119 E SQLiteDatabase: Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.,
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220),
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:23.028  7097  7119 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: Couldn't open MyDB.db for writing (will try read-only):
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
,07-01 08:58:23.028  7097  7119 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:23.028  7097  7119 W SQLiteOpenHelper: Opened MyDB.db in read-only mode
,07-01 08:58:23.038   966  1729 D Process : killProcessQuiet, pid=6622
07-01 08:58:23.038   966  1729 I ActivityManager: Killing 6622:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
07-01 08:58:23.038   966  1729 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-01 08:58:23.048   966  1673 I ActivityManager: Recipient 7067
,07-01 08:58:23.058  7120  7120 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-01 08:58:23.128   966  2384 I ActivityManager: Recipient 6622,
,07-01 08:58:23.148   966  1673 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 7067) has died
,07-01 08:58:23.148   966  1673 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 1000ms
,07-01 08:58:23.198  7120  7120 E SQLiteDatabase: Failed to open database '/data/data/com.android.providers.calendar/databases/calendar.db'.
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
,07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at com.android.providers.calendar.CalendarDatabaseHelper.getWritableDatabase(CalendarDatabaseHelper.java:2521)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at com.android.providers.calendar.CalendarProvider2.initialize(CalendarProvider2.java:592)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at com.android.providers.calendar.CalendarProvider2.onCreate(CalendarProvider2.java:567)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at com.htc.providers.calendar.HtcCalendarProvider.onCreate(HtcCalendarProvider.java:77)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-01 08:58:23.198  7120  7120 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-01 08:58:23.198  7120  7120 E CalendarProvider2: Cannot start provider
07-01 08:58:23.198  7120  7120 E CalendarProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at com.android.providers.calendar.CalendarDatabaseHelper.getWritableDatabase(CalendarDatabaseHelper.java:2521)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: ,	at com.android.providers.calendar.CalendarProvider2.initialize(CalendarProvider2.java:592)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at com.android.providers.calendar.CalendarProvider2.onCreate(CalendarProvider2.java:567)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at com.htc.providers.calendar.HtcCalendarProvider.onCreate(HtcCalendarProvider.java:77)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	,at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-01 08:58:23.198  7120  7120 E CalendarProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-01 08:58:23.258  7120  7145 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.flexnet/shared_prefs/com.htc.flexnet_preferences.xml to backup file /data/data/com.htc.flexnet/shared_prefs/com.htc.flexnet_preferences.xml.bak
,07-01 08:58:23.278   966  6515 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.PowerCommonReceiver: pid=7146 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-01 08:58:23.278   966  6515 D Process : killProcessQuiet, pid=6463
07-01 08:58:23.278   966  6515 I ActivityManager: Killing 6463:com.google.android.partnersetup/u0a27 (adj 15): empty #17
07-01 08:58:23.288   966  6515 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
,07-01 08:58:23.348   966  2384 I ActivityManager: Recipient 6463
,07-01 08:58:23.488   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 6
07-01 08:58:23.488   966   966 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 6
,07-01 08:58:23.538  7146  7146 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.PowerCommonReceiver.onReceive:20 android.app.ActivityThread.handleReceiver:2712 
,07-01 08:58:23.538   966   966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,07-01 08:58:23.548   966   966 D SmartDim: Init customizeScreenOffDelayClass error
,07-01 08:58:23.548  7120  7145 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.flexnet/shared_prefs/com.htc.flexnet_preferences.xml to backup file /data/data/com.htc.flexnet/shared_prefs/com.htc.flexnet_preferences.xml.bak
,07-01 08:58:23.558  7146  7167 D PowerUtils: getUserIdOfProcess, curUserId = 0
,07-01 08:58:23.558  7146  7167 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-01 08:58:23.558  7146  7146 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.PowerCommonReceiver.onReceive:20 android.app.ActivityThread.handleReceiver:2712 
,07-01 08:58:23.558   966   966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,07-01 08:58:23.568  7146  7167 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
07-01 08:58:23.568   966   966 I SensorManager: unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@10dd5791
07-01 08:58:23.568   966   966 W SensorService: Following SensorService logs are not warning, just make sure they are printed,
07-01 08:58:23.568   966   966 W SensorService: disable: get sensor name = Accelerometer Sensor
,07-01 08:58:23.568  7146  7168 D PowerUtils: getUserIdOfProcess, curUserId = 0,
07-01 08:58:23.568  7146  7168 D PowerUtils: isRunningUnderOwner, isOwner = true
07-01 08:58:23.568   966   966 W SensorService: pid=966, uid=1000
07-01 08:58:23.568   966   966 W SensorService: Active sensors: size = 3,
07-01 08:58:23.568   966   966 W SensorService: CM36686 Proximity sensor (handle=0x00000004, connections=1)
07-01 08:58:23.568   966   966 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-01 08:58:23.568   966   966 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
07-01 08:58:23.568   966   966 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@10dd5791, eanble = 0, strlen(mName) = 36
,07-01 08:58:23.568   966   966 W SensorService: Active Listeners: mActiveListeners.size() = 1
07-01 08:58:23.568   966   966 W SensorService: Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3f77a88a
07-01 08:58:23.568   966   966 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
07-01 08:58:23.568   966   966 W SensorService: Following SensorService logs are not warning, just make sure they are printed
07-01 08:58:23.568   966   966 W SensorService: disable: get sensor name = CM36686 Proximity sensor
,07-01 08:58:23.568   966   966 W SensorService: pid=966, uid=1000,
07-01 08:58:23.568   966   966 W SensorService: Active sensors: size = 2
07-01 08:58:23.568   966   966 W SensorService: Significant Motion (handle=0x0000000d, connections=1)
07-01 08:58:23.568   966   966 W SensorService: hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
07-01 08:58:23.568   966   966 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@10dd5791, eanble = 0, strlen(mName) = 36
07-01 08:58:23.568   966   966 W SensorService: Active Listeners: mActiveListeners.size() = 1,
07-01 08:58:23.568   966   966 W SensorService: Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3f77a88a
07-01 08:58:23.568   966   966 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
07-01 08:58:23.578  7146  7168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 
07-01 08:58:23.578   966  7169 I SensorManager: unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@10dd5791
07-01 08:58:23.578   966   966 E ActivityThread: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@2a12a6f6 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:23.578   966   966 E ActivityThread: android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@2a12a6f6 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:23.578   966   966 E ActivityThread: 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
07-01 08:58:23.578   966   966 E ActivityThread: 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
07-01 08:58:23.578   966   966 E ActivityThread: ,	at android.app.Service.onStartCommand(Service.java:458)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:23.578   966   966 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:23.578   966   966 E ActivityThread: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-01 08:58:23.578   966   966 E ActivityThread: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-01 08:58:23.578   966   966 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:23.578   966   966 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:23.578   966   966 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-01 08:58:23.578   966   966 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
07-01 08:58:23.578  7146  7167 D PowerUsageService: removed uid = 10195
07-01 08:58:23.578  7146  7168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:72 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 
,07-01 08:58:23.578  7146  7167 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:389)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2149)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:106)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:23.578  7146  7167 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:23.578  7146  7167 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
07-01 08:58:23.578  7146  7167 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 7146
07-01 08:58:23.578  7146  7167 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:389)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2149)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:106)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:23.578  7146  7167 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:23.578   966   989 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
07-01 08:58:23.578   966   989 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,07-01 08:58:23.588  7146  7168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:30 android.support.v4.content.LocalBroadcastManager.executePendingBroadcasts:297 android.support.v4.content.LocalBroadcastManager.sendBroadcastSync:278 
07-01 08:58:23.588   966  1665 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 08:58:23.588   966  1665 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:23.588   966  1665 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:23.588   966  1665 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:23.588   966  1665 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:23.588   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 08:58:23.588   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 08:58:23.588   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 08:58:23.588   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 08:58:23.588   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 08:58:23.588   966  1665 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 08:58:23.588   966  1665 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:23.588   966  1665 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:23.588   966  1665 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:23.588   966  1665 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:23.588   966  1665 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:23.588   966  1665 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:23.588   966  1665 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:23.588   966  1665 W System.err: 	... 12 more
07-01 08:58:23.588   966   989 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:23.588   966   989 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:23.588   966   989 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:23.588   966   989 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:23.588   966   989 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:23.588   966   989 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
,07-01 08:58:23.588   966   989 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
07-01 08:58:23.588   966   989 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
07-01 08:58:23.588   966   989 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:307)
07-01 08:58:23.588   966   989 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:23.588   966   989 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12583)
07-01 08:58:23.588   966   989 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12247)
07-01 08:58:23.588   966   989 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12219)
07-01 08:58:23.588   966   989 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
07-01 08:58:23.588   966   989 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
07-01 08:58:23.588   966   989 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,07-01 08:58:23.588   966   989 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:23.588   966   989 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:23.588   966   989 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:23.588   966   989 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:23.588   966   989 W System.err: 	... 14 more
,07-01 08:58:23.598  7146  7170 D ExtremePowerSaverMisc: epsInRange = 0
,07-01 08:58:23.598   966   989 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:23.598  1617  1840 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-01 08:58:23.598   966   989 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:23.598   966   989 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:23.598   966   989 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:23.598  1617  1840 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@16b996db +
07-01 08:58:23.598   966   989 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:23.598  1617  1840 I Prism.WidgetManager: onLoadItems() +
07-01 08:58:23.598   966   989 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
07-01 08:58:23.598   966   989 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
07-01 08:58:23.598   966   989 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
07-01 08:58:23.598   966   989 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:308)
07-01 08:58:23.598   966   989 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:23.598   966   989 W System.err: ,	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12583)
07-01 08:58:23.598   966   989 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12247)
07-01 08:58:23.598   966   989 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12219)
07-01 08:58:23.598   966   989 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
07-01 08:58:23.598   966   989 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
07-01 08:58:23.598   966   989 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:23.598   966   989 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:23.598   966   989 W ActivityManager: Process com.htc.htcpowermanager has crashed too many times: killing!
07-01 08:58:23.598   966   989 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:23.598   966   989 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:23.598   966   989 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:23.598   966   989 W System.err: 	... 14 more
,07-01 08:58:23.608   966   989 D Process : killProcessQuiet, pid=7146
07-01 08:58:23.608   966   989 I ActivityManager: Killing 7146:com.htc.htcpowermanager:remote/1000 (adj 0): crash
07-01 08:58:23.608   966  7174 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 08:58:23.608   966  7174 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467356303614.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 08:58:23.608   966  7174 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:23.608   966  7174 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:23.608   966  7174 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:23.608   966  7174 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:463)
07-01 08:58:23.608   966  7174 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:23.608   966  7174 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:23.608   966  7174 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:23.608   966  7174 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:23.608   966  7174 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:23.608   966  7174 E ErrorReport: 	... 4 more
07-01 08:58:23.608   966   989 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6372 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12139 
,07-01 08:58:23.638  1617  1840 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-01 08:58:23.648  2225  4990 I Icing   : Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox
,07-01 08:58:23.768   966  1673 I ActivityManager: Recipient 7146
,07-01 08:58:23.778  1617  1840 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 08:58:23.808   966   989 W ActivityManager: ProcessRecord{21f05790 7146:com.htc.htcpowermanager:remote/1000} has been replaced to new process null,
07-01 08:58:23.808   966  1673 W ActivityManager: Spurious death for ProcessRecord{21f05790 0:com.htc.htcpowermanager:remote/1000}, curProc for 7146: null

```
