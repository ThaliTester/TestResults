#### Test 757892686fd65a6_thali09_HTC-HTC One_M8 Logs


```
--------- beginning of system,
07-01 08:58:46.845   889   889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:817 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
07-01 08:58:47.145   889  1064 D PMS     : acquireWL(7eaa558): PARTIAL_WAKE_LOCK  *alarm* 0x1 889 1000 WorkSource{10075}
--------- beginning of main
07-01 08:58:47.155   889   889 E WifiStateMachine: WiFiStateMachine SCAN ALARM
07-01 08:58:47.155   889  1075 E WifiStateMachine: handleMessage: E msg.what=131143
07-01 08:58:47.155   889  1064 V AlarmManager: sending alarm PendingIntent{175966b1: PendingIntentRecord{1dd50fac com.android.vending startService}}, i=null, t=0, cnt=1, w=1467356327162, Int=0
07-01 08:58:47.155   889  1075 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:47.155   889  1064 V AlarmManager: sending alarm PendingIntent{39e8b4bd: PendingIntentRecord{1654bab2 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1467356314517, Int=20000
07-01 08:58:47.155   889  1075 E WifiStateMachine:  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2328 rssi=-51 f=2447 sc=60 link=150 tx=4.1, 0.0, 0.0  rx=7.9 fiv=40000 [on:0 tx:0 rx:0 period:644] from screen [on:0 period:-1522488063]
07-01 08:58:47.155   889   889 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
07-01 08:58:47.155   889   889 D WifiDisplayAdapter:     Client/Owner: Client
07-01 08:58:47.155   889   889 D WifiDisplayAdapter:     GroupId: 
07-01 08:58:47.155   889   889 D WifiDisplayAdapter:     Passphrase: 
07-01 08:58:47.155   889   889 D WifiDisplayAdapter:     SessionId: 0
07-01 08:58:47.155   889   889 D WifiDisplayAdapter:     IP Address: }
07-01 08:58:47.155   889  1075 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:47.155   889   889 D PMS     : releaseWL(7eaa558): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
07-01 08:58:47.155   889  1075 E WifiStateMachine:  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:2328 rssi=-51 f=2447 sc=60 link=150 tx=4.1, 0.0, 0.0  rx=7.9 fiv=40000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1522488061]
07-01 08:58:47.155   889  1075 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.06 rxSuccessRate=7.88 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-51
07-01 08:58:47.155   889  1075 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=79747 interval=40000 maxinterval=300000
07-01 08:58:47.155   889  1075 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=79747 interval=40000 maxinterval=300000
07-01 08:58:47.155   889  1075 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
07-01 08:58:47.155   889  1075 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =60000
07-01 08:58:47.155   889  1075 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
07-01 08:58:47.155  1344  1344 I wpa_supplicant: wpa_supplicant_scan enter
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS: Building WPS IE for Probe Request
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Request Type
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Config Methods (4288)
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * UUID-E
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Primary Device Type
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * RF Bands (3)
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Association State
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Configuration Error (0)
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Device Password ID (0)
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Manufacturer
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Model Name
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Model Number
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Device Name
07-01 08:58:47.155  1344  1344 D wpa_supplicant: WPS:  * Version2 (0x20)
07-01 08:58:47.155  1344  1344 D wpa_supplicant: P2P: * P2P IE header
07-01 08:58:47.155  1344  1344 D wpa_supplicant: P2P: * Capability dev=25 group=00
07-01 08:58:47.155  1344  1344 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 1
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: Add radio work 'scan'@0xb8a23158
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: Starting radio work 'scan'@0xb8a23158 after 0.000023 second wait
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: nl80211: scan request
07-01 08:58:47.155  1344  1344 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-01 08:58:47.155  1344  1344 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: nl80211: Scan trigger
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
07-01 08:58:47.155  1344  1344 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000050 seconds
07-01 08:58:47.155  1344  1344 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-01 08:58:47.155   889  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-01 08:58:47.155   889  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-01 08:58:47.155   889  1565 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-01 08:58:47.155   889  1565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-01 08:58:47.155   889  1075 E WifiStateMachine: [1,467,356,327,174 ms] noteScanstart no scan source
07-01 08:58:47.155   889  1075 E WifiStateMachine: handleMessage: X
07-01 08:58:47.275  6920  6920 D CustomizationManager: ====startRecUseTime====
07-01 08:58:47.275  6920  6920 D htc.customization.log.level:  is 
07-01 08:58:47.275  6920  6920 W CustomizationLogLevel: Level value is invalid, use default level 2
07-01 08:58:47.365  6920  6920 D CustomizationManager:  Read ACC file spent 0.045 (s)
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__001
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__102
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__203
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__405
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__304
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__032
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__016
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__A48
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__K18
07-01 08:58:47.365  6920  6920 D CIDMapFileReader: Parsing tag item name = HTC__002
07-01 08:58:47.365  6920  6920 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
07-01 08:58:47.375  6920  6920 I CustomizationCIDLoader: Parsing tag category name = system
07-01 08:58:47.375  6920  6920 I CustomizationCIDLoader: Parsing tag category name = application
07-01 08:58:47.375  6920  6920 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-01 08:58:47.375  6920  6920 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 08:58:47.375  6920  6920 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 08:58:47.375  6920  6920 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-01 08:58:47.375  6920  6920 I CustomizationCIDLoader: Parsing tag category name = ACC
07-01 08:58:47.375  6920  6920 D CustomizationManager:  Read CID file spent 0.097 (s)
07-01 08:58:47.375  6920  6920 D CustomizationManager:  All configurations done spent 0.097 (s)
07-01 08:58:47.395  6920  6920 E ActTriggerJNI: open library fail.
07-01 08:58:47.405  2351  2367 E MP-Decision: Update arg 2
07-01 08:58:47.405   889   905 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 08:58:47.415   889  1013 D PMS     : acquireHCC(c40d796): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 889 1000 null
07-01 08:58:47.415  2351  2367 E MP-Decision: Update arg 4
07-01 08:58:47.415   889  1013 D PMS     : acquireHCC(d4faf17): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 889 1000 null
07-01 08:58:47.415  2351  2367 E MP-Decision: Update arg "0 190 240 240".
07-01 08:58:47.415   889   905 D PMS     : acquireWL(132ad722): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 889 1000 null
07-01 08:58:47.415  2351  2367 E MP-Decision: Update arg "0 75 400 400".
07-01 08:58:47.415  1459  1459 I FeedHostManager: [onPause]
07-01 08:58:47.415  1459  1459 I FeedProviderManager: onPause
07-01 08:58:47.415  1459  2197 I SocialFeedProvider: +onPause
07-01 08:58:47.415  1459  2197 I SocialFeedProvider: -onPause
07-01 08:58:47.415  1459  1459 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@201c1dc1
07-01 08:58:47.425  6920  6950 E cutils-trace: Error opening trace file: No such file or directory (2)
07-01 08:58:47.425   889  1511 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-01 08:58:47.425   889   992 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/5
07-01 08:58:47.425   889   889 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 14 num clients 7
07-01 08:58:47.425   889   889 E WifiTrafficPoller:  packet count Tx=295 Rx=432
07-01 08:58:47.425   889   889 E WifiTrafficPoller: notifying of data activity 1
07-01 08:58:47.425  1119  1119 D WIFI_ICON: WifiActivity: 1
07-01 08:58:47.425  1119  1119 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-01 08:58:47.455   889  1301 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6954 uid=10192 gids={50192, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 08:58:47.455  1811  1811 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-01 08:58:47.475   889   889 V ActivityManager: Display changed displayId=0
07-01 08:58:47.475  1195  1195 D DotMatrix: [EventService]  onDisplayChanged: 0
07-01 08:58:47.475  1195  1195 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
07-01 08:58:47.485  1811  3092 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
07-01 08:58:47.485  1811  3092 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-01 08:58:47.485  1811  3092 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 08:58:47.485  1811  3092 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-01 08:58:47.485   889   990 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-01 08:58:47.485   889   990 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 08:58:47.485   889   990 D StatusBarManagerService: hiding MENU key
07-01 08:58:47.495  1811  3092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-01 08:58:47.505  5927  5927 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-01 08:58:47.505  5927  5927 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-01 08:58:47.505  5927  5927 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
07-01 08:58:47.515  1459  1459 I TrimMemoryManager: [trimMemory] 20
07-01 08:58:47.555  6954  6954 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-01 08:58:47.575  6954  6954 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3134-3135)
07-01 08:58:47.575  6954  6954 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:47.585  6954  6954 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1bdf1558}
07-01 08:58:47.585  6954  6954 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:47.585  6954  6954 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 08:58:47.605  6954  6954 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 08:58:47.605  6954  6954 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:47.605  6954  6954 E SysUtils: ApplicationContext is null in ApplicationStatus
07-01 08:58:47.615  6954  6954 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-01 08:58:47.625  6954  6954 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 08:58:47.625  6954  6954 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 08:58:47.625  6954  6954 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
07-01 08:58:47.625  6954  6954 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 08:58:47.625  6954  6954 I Adreno-EGL: Build Date: 12/11/14 Thu
07-01 08:58:47.625  6954  6954 I Adreno-EGL: Local Branch: 
07-01 08:58:47.625  6954  6954 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
07-01 08:58:47.625  6954  6954 I Adreno-EGL: Local Patches: NONE
07-01 08:58:47.625  6954  6954 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-01 08:58:47.675   889  2222 W System.err: java.lang.Throwable: stack dump
07-01 08:58:47.675   889  2222 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-01 08:58:47.675   889  2222 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
07-01 08:58:47.675   889  2222 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-01 08:58:47.675   889  2222 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:47.685   889   991 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-01 08:58:47.685   889   991 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e707993:true
07-01 08:58:47.685  6954  6986 D BluetoothAdapter: 288118195: getState(). Returning 12
07-01 08:58:47.745  6954  6954 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:47.755  6954  6954 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 08:58:47.765  6954  6954 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
07-01 08:58:47.765  6954  6954 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:47.765  6954  6954 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:47.805  6954  6954 D Atlas   : Validating map...
07-01 08:58:47.815  6954  6984 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-01 08:58:47.875  6954  6954 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@37375ca0, mServedView=org.apache.cordova.engine.SystemWebView{248b6059 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2489541e
07-01 08:58:47.875   889  2222 I InputMethodManagerService: Disable input method client, pid=1459
07-01 08:58:47.875   889  2222 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-01 08:58:47.875   889  2222 I InputMethodManagerService: Enable input method client, pid=6954
07-01 08:58:47.875   889  1139 D PMS     : releaseWL(132ad722): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
07-01 08:58:47.875   889   992 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +458ms
07-01 08:58:47.935  6954  6954 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6954
07-01 08:58:48.015  6954  6954 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-01 08:58:48.115  6954  7000 D jxcore_app_log: JniHelper::setJavaVM(0xb7c02b98), pthread_self() = -1192907336
07-01 08:58:48.115  6954  7000 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:58:48.115  6954  7000 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:48.115  6954  7000 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:48.115  6954  7000 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:48.115  6954  7000 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 08:58:48.115  6954  7000 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b57e82 added. We now have 1 listener(s)
07-01 08:58:48.125   889  2145 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 08:58:48.125  6954  7000 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 50:2E:6C:AC:21:50
07-01 08:58:48.125  6954  7000 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "50:2E:6C:AC:21:50"
07-01 08:58:48.125  6954  7000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 08:58:48.125  6954  7000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 50:2E:6C:AC:21:50
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 08:58:48.125  6954  7000 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22b811c9 added. We now have 1 listener(s)
07-01 08:58:48.125  6954  7000 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 08:58:48.135   889  1076 D WifiService: New client listening to asynchronous messages
07-01 08:58:48.135   889   889 E WifiTrafficPoller: ADD_CLIENT: 8
07-01 08:58:48.135  6954  7000 D BluetoothAdapter: 288118195: getState(). Returning 12
07-01 08:58:48.135  6954  7000 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-01 08:58:48.135  6954  7000 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-01 08:58:48.135  6954  7000 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-01 08:58:48.135  6954  7000 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 08:58:48.135   889  1302 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 08:58:48.135  6954  7000 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 50:2E:6C:AC:21:50
07-01 08:58:48.135  6954  7000 D BluetoothAdapter: 288118195: getState(). Returning 12
07-01 08:58:48.135  6954  7000 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:48.135  6954  7000 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:48.135  6954  7000 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 08:58:48.135  6954  7000 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 08:58:48.135  6954  7000 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 08:58:48.135  6954  7000 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 08:58:48.135  6954  7000 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 08:58:48.135  6954  7000 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 08:58:48.135  6954  7000 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 08:58:48.135  6954  7000 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 08:58:48.145  6954  6954 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 08:58:48.145  6954  7000 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 08:58:48.145  6954  6954 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 08:58:48.165  6954  6954 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 08:58:48.425   889   889 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 14 num clients 8
07-01 08:58:48.425   889   889 E WifiTrafficPoller:  packet count Tx=295 Rx=432
07-01 08:58:48.425   889   889 E WifiTrafficPoller: notifying of data activity 0
07-01 08:58:48.425  1119  1119 D WIFI_ICON: WifiActivity: 0
07-01 08:58:48.425  1119  1119 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
07-01 08:58:49.005  6954  7007 W jxcore-log: Initializing JXcore engine
07-01 08:58:49.005  6954  7007 W jxcore-log: JXcore engine is ready
07-01 08:58:49.065  6954  7007 W jxcore-log: Starting JXcore engine
,07-01 08:58:49.135  6954  7007 W jxcore-log: Platform android,
07-01 08:58:49.135  6954  7007 W jxcore-log: 
07-01 08:58:49.135  6954  7007 W jxcore-log: Process ARCH arm
07-01 08:58:49.135  6954  7007 W jxcore-log: 
,07-01 08:58:49.305   889   889 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 4,
,07-01 08:58:49.305   889  7009 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=275 rxSum=258} preTxRxSum={txSum=275 rxSum=258}
07-01 08:58:49.305   889  7009 D WifiDataStallTracker: updateDataStallInfo: NONE
,07-01 08:58:49.305   889  7009 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-01 08:58:49.345  1344  1344 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: nl80211: New scan results available
07-01 08:58:49.345  1344  1344 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
07-01 08:58:49.345  1344  1344 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: Scan completed in 2.184130 seconds
07-01 08:58:49.345  1344  1344 D wpa_supplicant: nl80211: Associated on 2447 MHz
07-01 08:58:49.345  1344  1344 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
,07-01 08:58:49.345  1344  1344 D wpa_supplicant: nl80211: Received scan results (11 BSSes)
07-01 08:58:49.345   889  1075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:13935 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14100 com.android.server.wifi.WifiStateMachine.access$5400:265 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7908 
07-01 08:58:49.345  1344  1344 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2447 level=-46
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2447 level=-51
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-60
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-60
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] 84:b2:61:0f:9c:32 freq=2462 level=-77
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] 00:1a:ef:42:f2:b0 freq=2412 level=-82
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] 00:16:a6:1f:06:5c freq=2462 level=-83
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] f4:f2:6d:85:e5:9e freq=2412 level=-88
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] 84:b2:61:21:47:54 freq=2437 level=-91
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] 84:b2:61:1a:ce:73 freq=2412 level=-80
07-01 08:58:49.345  1344  1344 I wpa_supplicant: [NULL] 84:b2:61:21:47:53 freq=2437 level=-90
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: BSS: Start scan result update 9
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: BSS: Add new id 18 BSSID 84:b2:61:0f:9c:32 SSID '\x00'
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: BSS: Remove id 9 BSSID 84:b2:61:1a:ce:70 SSID '\x00' due to no match in scan
07-01 08:58:49.345   889  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 18 84:b2:61:0f:9c:32]
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: BSS: Remove id 10 BSSID 00:16:a6:1e:e0:a4 SSID '' due to no match in scan
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: BSS: Remove id 11 BSSID 84:b2:61:0f:9c:33 SSID 'RA-WINGS' due to no match in scan
07-01 08:58:49.345   889  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 84:b2:61:1a:ce:70]
07-01 08:58:49.345   889  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 84:b2:61:1a:ce:70
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: BSS: Remove id 6 BSSID 84:b2:61:12:64:93 SSID 'RA-WINGS' due to no match in scan
07-01 08:58:49.345   889  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:16:a6:1e:e0:a4]
07-01 08:58:49.345  1344  1344 D wpa_supplicant: BSS: last_scan_res_used=11/32
07-01 08:58:49.345   889  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:16:a6:1e:e0:a4
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: Scan-only results received
07-01 08:58:49.345   889  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 84:b2:61:0f:9c:33]
07-01 08:58:49.345   889  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 84:b2:61:0f:9c:33
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: Radio work 'scan'@0xb8a23158 done in 2.185056 seconds
07-01 08:58:49.345   889  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 84:b2:61:12:64:93]
07-01 08:58:49.345   889  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 84:b2:61:12:64:93
07-01 08:58:49.345  1344  1344 D wpa_supplicant: Wireless event: cmd=0x8b19 len=8
07-01 08:58:49.345  1344  1344 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
07-01 08:58:49.345   889  1565 E WifiMonitor: WifiMonitor:wla,n0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-01 08:58:49.345   889  1565 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-01 08:58:49.345   889  1075 E WifiStateMachine: handleMessage: E msg.what=147461
07-01 08:58:49.345   889  1075 E WifiStateMachine: processMsg: ConnectedState
07-01 08:58:49.345   889  1075 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=16 known=1 got=16 bcn=0
07-01 08:58:49.345   889  1075 E WifiStateMachine: processMsg: L2ConnectedState
07-01 08:58:49.345   889  1075 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=16 known=1 got=16 bcn=0
07-01 08:58:49.345   889  1075 E WifiStateMachine: processMsg: ConnectModeState
07-01 08:58:49.345   889  1075 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=16 known=1 got=16 bcn=0
07-01 08:58:49.345   889  1075 E WifiStateMachine: processMsg: DriverStartedState
07-01 08:58:49.345   889  1075 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=16 known=1 got=16 bcn=0
07-01 08:58:49.345   889  1075 E WifiStateMachine: processMsg: SupplicantStartedState
07-01 08:58:49.345   889  1075 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=16 known=1 got=16 bcn=0
07-01 08:58:49.345   889  1075 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
07-01 08:58:49.345   889  1075 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
07-01 08:58:49.345   889   989 D Tethering: interfaceLinkStateChanged wlan0, true
07-01 08:58:49.345   889   989 D Tethering: interfaceStatusChanged wlan0, true
07-01 08:58:49.345   889   989 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-01 08:58:49.345   889  1075 E WifiStateMachine: [1,467,356,329,359 ms] noteScanEnd no scan source
07-01 08:58:49.345   889  1075 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
07-01 08:58:49.345   889  1082 D WirelessDisplayService: getDiscoveryDongleList
07-01 08:58:49.345   889  1075 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@1f4789ea sup_state=COMPLETED debouncing=false
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
07-01 08:58:49.345   889  1075 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
07-01 08:58:49.345   889  1075 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-51 freq=2447
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-60 cap [WPA2-EAP-TKIP][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-60 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : RA-WINGS 84:b2:61:1a:ce:73 rssi=-80 cap [ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController :  84:b2:61:1a:ce:72 rssi=-76 cap [WPA2-PSK-CCMP][ESS] is not scored
,07-01 08:58:49.345   889  1075 E WifiAutoJoinController :  84:b2:61:1a:ce:74 rssi=-76 cap [WPA2-EAP-CCMP][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : RA-WINGS 84:b2:61:21:47:53 rssi=-90 cap [ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-46 cap [WPA2-PSK-CCMP][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : Conrad_AP 00:1a:ef:42:f2:b0 rssi=-82 cap [WPA-PSK-CCMP][WPS][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : cvbtemp f4:f2:6d:85:e5:9e rssi=-88 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController :  84:b2:61:21:47:54 rssi=-91 cap [WPA2-EAP-CCMP][ESS] is not scored
,07-01 08:58:49.345   889  1075 E WifiAutoJoinController :  00:16:a6:1f:06:5c rssi=-83 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController :  84:b2:61:0f:9c:32 rssi=-77 cap [WPA2-PSK-CCMP][ESS] is not scored
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 19 now 1467356329363
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : newSupplicantResults size=17 known=1 true
07-01 08:58:49.345   889  1075 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
07-01 08:58:49.345  1344  1344 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : ssid=NG700
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : id=2
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : mode=station
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : pairwise_cipher=CCMP
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : group_cipher=CCMP
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : key_mgmt=WPA2-PSK
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : wpa_state=COMPLETED
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : ip_address=192.168.1.130
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : p2p_device_address=02:ee:bd:dd:33:d2
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=2
,07-01 08:58:49.345   889  1075 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-51,-127) num=(1,0)
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : attemptAutoJoin skip current candidate  2 key "NG700"WPA_PSK
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-51 freq=2447 Current: f4:f2:6d:22:99:3e
07-01 08:58:49.345   889  1075 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
07-01 08:58:49.345   889  1075 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-01 08:58:49.345   889  1075 E WifiAutoJoinController : Done attemptAutoJoin status=0
07-01 08:58:49.345   889  1075 E WifiConfigStore:  writeKnownNetworkHistory() num networks:4 needWrite=false
07-01 08:58:49.345  6954  7007 I jxcore-log: JXcore Cordova bridge is ready!
07-01 08:58:49.345  6954  7007 I jxcore-log: 
07-01 08:58:49.345  6954  7007 W jxcore-log: JXcore engine is started
,07-01 08:58:49.345  1751  1751 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10025
07-01 08:58:49.345   889  1075 E WifiStateMachine: handleMessage: X
07-01 08:58:49.345   889  1082 D WirelessDisplayService: getDiscoveryDongleList
07-01 08:58:49.355  6954  7000 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-01 08:58:49.355  6954  6954 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 08:58:49.355  6954  7007 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-01 08:58:49.355  6954  7007 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 08:58:49.365  6954  6954 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-01 08:58:49.365  6954  6954 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 08:58:49.395  6954  6954 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
07-01 08:58:49.395   889  1520 D PMS     : acquireWL(241f9ead): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 889 1000 null
07-01 08:58:49.395  6954  6954 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-01 08:58:49.395  6954  7000 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
07-01 08:58:49.395  2351  2367 E MP-Decision: Update arg "0 380 380 380".
,07-01 08:58:49.395  2351  2367 E MP-Decision: Update arg "0 400 400 400".
07-01 08:58:49.395   889  1511 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-01 08:58:49.405   889  1013 D PMS     : releaseHCC(c40d796): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
07-01 08:58:49.405   889  1013 D PMS     : releaseHCC(d4faf17): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-01 08:58:49.415  2351  2367 E MP-Decision: Update arg 1
07-01 08:58:49.415  1459  1459 I FeedHostManager: [onResume]
07-01 08:58:49.415  1459  1459 I FeedProviderManager: onResume
07-01 08:58:49.415  1459  2197 I SocialFeedProvider: +onResume
07-01 08:58:49.415  1459  2197 I SocialFeedProvider: updateAccounts - Accounts is no change
07-01 08:58:49.415  1459  2197 I SocialFeedProvider: -onResume
,07-01 08:58:49.425   889   990 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-01 08:58:49.425   889   990 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
07-01 08:58:49.425   889   990 D StatusBarManagerService: hiding MENU key
,07-01 08:58:49.425   889   889 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 14 num clients 8
,07-01 08:58:49.425   889   889 E WifiTrafficPoller:  packet count Tx=295 Rx=432
,07-01 08:58:49.435   889  1520 I InputMethodManagerService: Disable input method client, pid=6954
07-01 08:58:49.435   889  1520 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-01 08:58:49.435   889  1520 I InputMethodManagerService: Enable input method client, pid=1459
,07-01 08:58:49.435  6954  6954 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-01 08:58:49.455   889   990 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
07-01 08:58:49.455   889   990 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 08:58:49.455   889   990 D StatusBarManagerService: hiding MENU key
07-01 08:58:49.455   889   904 D PMS     : releaseWL(241f9ead): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-01 08:58:49.475   889   984 D Process : killProcessQuiet, pid=6414
,07-01 08:58:49.475   889   984 I ActivityManager: Killing 6414:com.android.defcontainer/u0a15 (adj 15): empty #17
07-01 08:58:49.485   889   984 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityStack.destroyActivityLocked:3417 
07-01 08:58:49.485   889  1669 I ActivityManager: Recipient 6414
,07-01 08:58:49.495   889  1075 E WifiStateMachine: handleMessage: E msg.what=131155
07-01 08:58:49.495   889  1075 E WifiStateMachine: processMsg: ConnectedState
,07-01 08:58:49.505   889  1075 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=150 tx=4.1, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:2342] from screen [on:0 period:-1522485716] gl hn u24 rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 08:58:49.505   889  1075 E WifiStateMachine: processMsg: L2ConnectedState
,07-01 08:58:49.505   889  1075 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=150 tx=4.1, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1522485715] gl hn u24 rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 08:58:49.505   889  1075 E WifiStateMachine:  get link layer stats 0
07-01 08:58:49.505   889  1075 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-01 08:58:49.505  1344  1344 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-01 08:58:49.515  1344  1344 I wpa_supplicant: environment dirty rate=0 [0][0][0]
07-01 08:58:49.515   889  1075 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 150
07-01 08:58:49.515   889  1075 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-48 linkspeed=150
07-01 08:58:49.515   889  1075 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-49 "NG700"WPA_PSK
07-01 08:58:49.515   889  1075 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.03 txretriesrate=0.00 rxrate=6.94 userTriggerdPenalty0
07-01 08:58:49.515   889  1075 E WifiStateMachine:  good link -> stuck count =0
07-01 08:58:49.515   889  1075 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
07-01 08:58:49.515   889  1075 E WifiStateMachine:  isHighRSSI       ---> score=61
,07-01 08:58:49.545  6954  6954 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
07-01 08:58:49.545  6954  6954 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-01 08:58:49.545   889  1669 W libprocessgroup: failed to open /acct/uid_10015/pid_6414/cgroup.procs: No such file or directory
07-01 08:58:49.545  6954  6954 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 08:58:49.545  6954  6954 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-01 08:58:49.545  6954  6954 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-01 08:58:49.545   889  1669 D Process : killProcessQuiet, pid=6414
07-01 08:58:49.545   889  1669 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-01 08:58:49.545  6954  6954 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 08:58:49.545  6954  6954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 08:58:49.545  6954  6954 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-01 08:58:49.545  6954  6954 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b57e82 removed from the list
07-01 08:58:49.545  6954  6954 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-01 08:58:49.545  6954  6954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22b811c9 removed from the list
07-01 08:58:49.545  6954  6954 D io.jxcore.node.ConnectivityMonitor: stop
07-01 08:58:49.545  6954  6954 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-01 08:58:49.545   889  1075 E WifiStateMachine: handleMessage: X
07-01 08:58:49.545   889  1092 D WifiWatchdogStateMachine: RSSI current: 3 new: -48, 3
07-01 08:58:49.545  6954  6954 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 08:58:49.565  1119  1119 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3,
07-01 08:58:49.565  1119  1119 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-01 08:58:49.645  7011  7014 E cutils-trace: Error opening trace file: No such file or directory (2)
,07-01 08:58:49.685  7011  7011 D CustomizationManager: ====startRecUseTime====
,07-01 08:58:49.685  7011  7011 D htc.customization.log.level:  is 
07-01 08:58:49.685  7011  7011 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-01 08:58:49.785  7011  7011 D CustomizationManager:  Read ACC file spent 0.051 (s)
,07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__001,
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__102
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__203
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__405
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__304
,07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__032
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__016
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__A48
07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__K18
,07-01 08:58:49.785  7011  7011 D CIDMapFileReader: Parsing tag item name = HTC__002
07-01 08:58:49.785  7011  7011 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
07-01 08:58:49.785  7011  7011 I CustomizationCIDLoader: Parsing tag category name = system
,07-01 08:58:49.785  7011  7011 I CustomizationCIDLoader: Parsing tag category name = application
,07-01 08:58:49.785  7011  7011 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,07-01 08:58:49.785  7011  7011 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 08:58:49.785  7011  7011 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 08:58:49.785  7011  7011 I CustomizationCIDLoader: Parsing tag category name = AudioService
,07-01 08:58:49.785  7011  7011 I CustomizationCIDLoader: Parsing tag category name = ACC
07-01 08:58:49.785  7011  7011 D CustomizationManager:  Read CID file spent 0.100 (s)
07-01 08:58:49.785  7011  7011 D CustomizationManager:  All configurations done spent 0.100 (s)
,07-01 08:58:49.805  7011  7011 E ActTriggerJNI: open library fail.
,07-01 08:58:49.815   889  1240 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=7011, uid=2000 userid=0
,07-01 08:58:49.825   889   984 D Process : killProcessQuiet, pid=6954
,07-01 08:58:49.825   889   984 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=-1: uninstall pkg
07-01 08:58:49.825   889   984 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
07-01 08:58:49.825   889   984 I ActivityManager: Killing 6954:com.test.thalitest/u0a192 (adj 9): stop com.test.thalitest
,07-01 08:58:49.845   889  1302 I ActivityManager: Recipient 6954,
07-01 08:58:49.845  1279  1279 E InputEventReceiver: Looper::removeFd(67) is failed, result(0), input channel 'ClientState{35873b00 uid 10192 pid 6954} (c)'
07-01 08:58:49.845   889  1076 D WifiService: Client connection lost with reason: 4
,07-01 08:58:49.895   889  1049 W PackageSettings: Skipping PackageSetting{27e54227 com.example.hello/10380} due to missing metadata,
,07-01 08:58:49.935   889  1302 W ActivityManager: Spurious death for ProcessRecord{2ff5e7eb 6954:com.test.thalitest/u0a192}, curProc for 6954: null
,07-01 08:58:49.935   889  1049 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=0: pkg removed
,07-01 08:58:49.945  1195  1195 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,07-01 08:58:49.945   889  1520 D PMS     : acquireWL(231f8948): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1751 10025 WorkSource{10025 com.google.android.gms},
,07-01 08:58:49.945  1195  1195 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false,
07-01 08:58:49.955   889  1240 D PMS     : releaseWL(231f8948): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
07-01 08:58:49.945  1195  1195 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
07-01 08:58:49.965   889  1072 D PMS     : acquireWL(3847f1f4): PARTIAL_WAKE_LOCK  NetworkStats 0x1 889 1000 null
07-01 08:58:49.955  1593  2031 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-01 08:58:49.965   889  1073 V NetworkPolicy: ACTION_UID_REMOVED for uid=10192,
07-01 08:58:49.965  1593  2031 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-01 08:58:49.995   889  1072 D PMS     : releaseWL(3847f1f4): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-01 08:58:49.975  1397  1397 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-01 08:58:49.995   889  1073 V NetworkPolicy: writePolicyLocked()
07-01 08:58:49.975  1459  1459 I art     : Explicit concurrent mark sweep GC freed 25252(1608KB) AllocSpace objects, 21(1849KB) LOS objects, 39% free, 18MB/30MB, paused 542us total 46.599ms,
07-01 08:58:49.985  6512  6512 I art     : Explicit concurrent mark sweep GC freed 418(28KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 454us total 40.861ms
07-01 08:58:49.985  1577  7025 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-01 08:58:49.995  1459  1863 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-01 08:58:49.995  1459  1863 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-01 08:58:49.995  1459  1868 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,07-01 08:58:50.015  1459  1459 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
,07-01 08:58:50.025  1524  7026 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
,07-01 08:58:50.025  1524  7026 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed,
,07-01 08:58:50.025   889  1073 V NetworkPolicy: updateNetworkEnabledLocked()
07-01 08:58:50.025   889  1073 V NetworkPolicy: updateNotificationsLocked()
07-01 08:58:50.025   889   983 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,07-01 08:58:50.045  1593  2031 E ExternalAccountType: Unsupported attribute readOnly,
,07-01 08:58:50.045   889   889 I art     : Explicit concurrent mark sweep GC freed 43237(2MB) AllocSpace objects, 5(628KB) LOS objects, 33% free, 19MB/28MB, paused 1.373ms total 100.544ms
07-01 08:58:50.045   889  1049 I art     : WaitForGcToComplete blocked for 76.089ms for cause Explicit
,07-01 08:58:50.045   889   905 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,07-01 08:58:50.095   889   889 W PackageManager: Unable to load service info ResolveInfo{3ccf8b45 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-01 08:58:50.095   889   889 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-01 08:58:50.095   889   889 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
07-01 08:58:50.095   889   889 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
07-01 08:58:50.095   889   889 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-01 08:58:50.095   889   889 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-01 08:58:50.095   889   889 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-01 08:58:50.095   889   889 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-01 08:58:50.095   889   889 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 08:58:50.095   889   889 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 08:58:50.095   889   889 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:50.095   889   889 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-01 08:58:50.095   889   889 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-01 08:58:50.095   889   889 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:50.095   889   889 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:50.095   889   889 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
07-01 08:58:50.095   889   889 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,07-01 08:58:50.135  7027  7027 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,07-01 08:58:50.155   889   983 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-01 08:58:50.165   889  1049 I art     : Explicit concurrent mark sweep GC freed 7697(446KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/28MB, paused 1.448ms total 118.330ms,
,07-01 08:58:50.165  1811  1811 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-01 08:58:50.165   889  1520 D PMS     : acquireWL(dfc5d49): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1811 10025 WorkSource{10025 com.google.android.gms}
07-01 08:58:50.165  1811  1811 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-01 08:58:50.175   889  1669 D PMS     : releaseWL(dfc5d49): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,07-01 08:58:50.185  4326  4326 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games,
07-01 08:58:50.185  4326  4326 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-01 08:58:50.185  4326  7051 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
,07-01 08:58:50.185  4326  4326 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,07-01 08:58:50.185  4326  4326 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-01 08:58:50.185  4326  7051 D AccountUtils: Clearing selected account for com.test.thalitest
,07-01 08:58:50.195   889   889 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-01 08:58:50.205  6512  7054 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-01 08:58:50.215   889  1139 D PMS     : acquireWL(20b938ac): PARTIAL_WAKE_LOCK  AsyncService 0x1 6597 10176 null
,07-01 08:58:50.215   889   904 D PMS     : releaseWL(20b938ac): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-01 08:58:50.215   889  2222 D PMS     : acquireWL(20c3cd0a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6597 10176 null
,07-01 08:58:50.225  6627  6627 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,07-01 08:58:50.225   889  1520 D PMS     : releaseWL(20c3cd0a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,07-01 08:58:50.235  6627  6627 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,07-01 08:58:50.235  4326  7051 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest,
,07-01 08:58:50.235  6627  6627 I DeviceManagement: WorkflowService: Starting workflow service,
,07-01 08:58:50.235  6627  7059 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@26e2c796] args=[Bundle[mParcelledData.dataSize=112]]
07-01 08:58:50.235  6627  7059 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-01 08:58:50.235  6627  7059 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
07-01 08:58:50.235  6627  7059 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,07-01 08:58:50.245  6627  7059 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,07-01 08:58:50.265   889  1301 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7060 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,07-01 08:58:50.275   466   466 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 143us total 10.025ms,
07-01 08:58:50.275  6627  7059 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,07-01 08:58:50.285   466   466 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 133us total 9.087ms,
,07-01 08:58:50.295   466   466 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 136us total 9.354ms
,07-01 08:58:50.295  6627  7077 I DeviceManagement: SessionStateController: Checking invariants...,
,07-01 08:58:50.305  4326  7058 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,07-01 08:58:50.305  4326  7058 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-01 08:58:50.305  4326  7058 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-01 08:58:50.305  4326  7058 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,07-01 08:58:50.305   889  1240 D PMS     : acquireWL(126f7999): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4326 10025 null
,07-01 08:58:50.305  1811  1811 I ConfigService: onCreate,
,07-01 08:58:50.305  4326  7058 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,07-01 08:58:50.305  4326  7058 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-01 08:58:50.305  4326  7058 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,07-01 08:58:50.315  4326  4326 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
07-01 08:58:50.315   889  1523 D PMS     : releaseWL(126f7999): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,07-01 08:58:50.315  4326  7058 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,07-01 08:58:50.325  4326  7078 W BaseAppContext: Using Auth Proxy for data requests.,
07-01 08:58:50.325  4326  7058 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,07-01 08:58:50.325  4326  7078 W BaseAppContext: Using Auth Proxy for data requests.,
07-01 08:58:50.325  4326  7058 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,07-01 08:58:50.325  4326  7058 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,07-01 08:58:50.325  4326  7058 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
07-01 08:58:50.325  4326  7058 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,07-01 08:58:50.365   889  1262 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7084 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a,
,07-01 08:58:50.365  6743  6743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,07-01 08:58:50.365  4326  7087 I PeopleContactsSync: CP2 sync disabled,
07-01 08:58:50.365   889  1301 D PMS     : acquireWL(378c772f): PARTIAL_WAKE_LOCK  Icing 0x1 4326 10025 WorkSource{10025 com.google.android.gms}
07-01 08:58:50.365   889  2145 I ActivityManager: Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,07-01 08:58:50.375  6743  7098 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
07-01 08:58:50.375   889  1301 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4326, uid=10025, userID:0
07-01 08:58:50.375   889  1669 I ActivityManager: Resuming delayed broadcast
07-01 08:58:50.375  6743  7098 D PowerUsageService: removed uid = 10192
,07-01 08:58:50.385  4326  4406 I Icing   : doRemovePackageData com.test.thalitest
,07-01 08:58:50.405  7084  7084 D ExternalStorage: After updating volumes, found 1 active roots,
,07-01 08:58:50.425   889  2146 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=7104 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
,07-01 08:58:50.425   889   889 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 14 num clients 7
,07-01 08:58:50.425   889   889 E WifiTrafficPoller:  packet count Tx=295 Rx=432
,07-01 08:58:50.455  6627  7077 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,07-01 08:58:50.465   889  1049 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7123 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=armeabi-v7a
,07-01 08:58:50.475  6512  7054 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 274 ms] updated apps [took 274 ms] 
,07-01 08:58:50.485  7104  7104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 08:58:50.505   889  2146 D Process : killProcessQuiet, pid=6461,
07-01 08:58:50.505   889  2146 I ActivityManager: Killing 6461:com.google.android.talk/u0a120 (adj 15): empty #17,
07-01 08:58:50.505   889  2146 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,07-01 08:58:50.515   889  1262 I ActivityManager: Recipient 6461
,07-01 08:58:50.565   889  1262 D Process : killProcessQuiet, pid=6461
,07-01 08:58:50.565   889  1262 W libprocessgroup: failed to open /acct/uid_10120/pid_6461/cgroup.procs: No such file or directory
07-01 08:58:50.565   889  1262 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,07-01 08:58:50.565  6627  7059 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,07-01 08:58:50.575  6627  7059 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@26e2c796]
,07-01 08:58:50.575  6627  6627 I DeviceManagement: WorkflowService: Stopping workflow service
,07-01 08:58:50.575   889  1667 D Process : killProcessQuiet, pid=6549
07-01 08:58:50.575   889  1667 I ActivityManager: Killing 6549:com.google.android.partnersetup/u0a28 (adj 15): empty #17
07-01 08:58:50.575   889  1667 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,07-01 08:58:50.585   889  2145 I ActivityManager: Recipient 6549
,07-01 08:58:50.605   889  2145 D Process : killProcessQuiet, pid=6549
07-01 08:58:50.605   889  2145 W libprocessgroup: failed to open /acct/uid_10028/pid_6549/cgroup.procs: No such file or directory
07-01 08:58:50.605   889  2145 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,07-01 08:58:50.615   889  1302 D Process : killProcessQuiet, pid=6645,
07-01 08:58:50.615   889  1302 I ActivityManager: Killing 6645:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
07-01 08:58:50.615   889  1302 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,07-01 08:58:50.625  6678  6678 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
07-01 08:58:50.625   889  1301 I ActivityManager: Recipient 6645
07-01 08:58:50.625  6678  6678 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 08:58:50.645   889  1301 D Process : killProcessQuiet, pid=6645
,07-01 08:58:50.645   889  1301 W libprocessgroup: failed to open /acct/uid_10013/pid_6645/cgroup.procs: No such file or directory
07-01 08:58:50.645   889  1301 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,07-01 08:58:50.655  7060  7082 D Documents: Update found 7 roots in 322ms,
,07-01 08:58:50.655  7060  7106 D Documents: Update found 7 roots in 244ms,
,07-01 08:58:50.675  1811  2801 I art     : Explicit concurrent mark sweep GC freed 9455(490KB) AllocSpace objects, 2(32KB) LOS objects, 48% free, 4MB/8MB, paused 870us total 24.307ms
,07-01 08:58:50.685  4326  7057 W DriveInitializer: Awaiting to be initialized
,07-01 08:58:50.685  4326  7146 W DriveInitializer: Background init thread started
,07-01 08:58:50.725   361   406 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
,07-01 08:58:50.725   361   406 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 08:58:50.725  4326  7146 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,07-01 08:58:50.765  4326  7146 W DriveInitializer: Background init thread ended,
,07-01 08:58:50.795  4326  4340 W art     : Suspending all threads took: 6.896ms
,07-01 08:58:50.835  1811  7161 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.,
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:50.835  1811  7161 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187),
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:50.835  1811  7161 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,07-01 08:58:50.835  1811  7161 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
07-01 08:58:50.835  1811  7161 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:585)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:50.835  1811  7161 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:585)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:50.835  1811  7161 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,07-01 08:58:51.425   889   889 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 14 num clients 7,
07-01 08:58:51.435  1119  1119 D WIFI_ICON: WifiActivity: 1
07-01 08:58:51.435   889   889 E WifiTrafficPoller:  packet count Tx=295 Rx=433
,07-01 08:58:51.435  1119  1119 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T],
07-01 08:58:51.435   889   889 E WifiTrafficPoller: notifying of data activity 1
,07-01 08:58:51.495  1459  1863 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
,07-01 08:58:51.495  1459  1863 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@19f16099 +,
,07-01 08:58:51.545  1459  1863 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-01 08:58:51.495  1459  1863 I Prism.WidgetManager: onLoadItems() +
07-01 08:58:51.515  4326  4406 I Icing   : Indexing 133D3F44B423C1F90B90CE261AE1222BFA42C728 from com.google.android.googlequicksearchbox
,07-01 08:58:51.685  4326  4406 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
07-01 08:58:51.685  4326  4406 E Icing   : Could not init tag ds.tag.deleted
,07-01 08:58:51.705  4326  4406 I Icing   : Indexing done 133D3F44B423C1F90B90CE261AE1222BFA42C728
,07-01 08:58:51.705   889  1667 D PMS     : releaseWL(378c772f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,07-01 08:58:51.705   889  1520 D Process : killProcessQuiet, pid=6487
07-01 08:58:51.705   889  1520 I ActivityManager: Killing 6487:com.htc.sense.mms/u0a67 (adj 15): empty #17
07-01 08:58:51.705   889  1520 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-01 08:58:51.705  1459  1863 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 08:58:51.715   889  1667 I ActivityManager: Recipient 6487
,07-01 08:58:51.745   889  1667 D Process : killProcessQuiet, pid=6487
,07-01 08:58:51.745   889  1667 W libprocessgroup: failed to open /acct/uid_10067/pid_6487/cgroup.procs: No such file or directory
07-01 08:58:51.745   889  1667 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,07-01 08:58:51.765  1459  1863 E Prism.WidgetManager: The same lists. No need to update. skip it.
,07-01 08:58:51.765  1459  1863 I Prism.WidgetManager: onLoadItems() -
07-01 08:58:51.765  1459  1863 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@19f16099 -
,07-01 08:58:51.765  1459  1863 E SQLiteLog: (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=73] disk I/O error
,07-01 08:58:51.765  1459  1863 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xb8cc42b0
,07-01 08:58:51.775  1459  1863 E AndroidRuntime: FATAL EXCEPTION: TaskWorker
07-01 08:58:51.775  1459  1863 E AndroidRuntime: Process: com.htc.launcher, PID: 1459
07-01 08:58:51.775  1459  1863 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.775  1459  1863 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:51.775   889  1240 E ActivityManager: App crashed! Process: com.htc.launcher
07-01 08:58:51.775   889  1240 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,07-01 08:58:51.775   889  1511 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system),
07-01 08:58:51.775   889  1511 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:51.775   889  1511 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:51.775   889  1511 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:51.775   889  1511 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:51.775   889  1511 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 08:58:51.775   889  1511 W System.err: ,	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 08:58:51.775   889  1511 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 08:58:51.775   889  1511 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 08:58:51.785   889  1511 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 08:58:51.785   889  1511 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 08:58:51.785   889  1511 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.785   889  1511 W System.err: ,	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.785   889  1511 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:51.785   889  1511 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:51.785   889  1511 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:51.785   889  1511 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:51.785   889  1511 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:51.785   889  1511 W System.err: 	... 12 more
,07-01 08:58:51.785   889  1240 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
,07-01 08:58:51.785   889  1240 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:51.785   889  1240 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:51.785   889  1240 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:51.785   889  1240 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:51.785   889  1240 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
07-01 08:58:51.785   889  1240 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
07-01 08:58:51.785   889  1240 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
07-01 08:58:51.785   889  1240 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
07-01 08:58:51.785   889  1240 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
07-01 08:58:51.785   889  1240 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
07-01 08:58:51.785   889  1240 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
07-01 08:58:51.785   889  1240 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
07-01 08:58:51.785   889  1240 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
07-01 08:58:51.785   889  1240 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
07-01 08:58:51.785   889  1240 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:51.785   889  1240 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:51.785   889  1240 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:51.785   889  1240 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:51.785   889  1240 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:51.785   889  1240 W System.err: 	... 14 more
,07-01 08:58:51.795   889  1240 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
07-01 08:58:51.795   889  1240 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:51.795   889  1240 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:51.795   889  1240 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:51.795   889  1240 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:51.795   889  1240 W System.err: ,	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
07-01 08:58:51.795   889  1240 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
07-01 08:58:51.795   889  1240 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
07-01 08:58:51.795   889  1240 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
07-01 08:58:51.795   889  1240 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
07-01 08:58:51.795   889  1240 W System.err: ,	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
07-01 08:58:51.795   889  1240 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
07-01 08:58:51.795   889  1240 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
07-01 08:58:51.795   889  1240 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
07-01 08:58:51.795   889  1240 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
07-01 08:58:51.795   889  1240 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:51.795   889  1240 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:51.795   889  1240 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:51.795   889  1240 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:51.795   889  1240 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:51.795   889  1240 W System.err: 	... 14 more
,07-01 08:58:51.795   889  1240 W ActivityManager:   Force finishing activity com.htc.launcher/.Launcher
,07-01 08:58:51.795   889  1240 D PMS     : acquireWL(3706335): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 889 1000 null
07-01 08:58:51.795  1459  1459 I FeedHostManager: [onPause]
,07-01 08:58:51.795  1459  1459 I FeedProviderManager: onPause
07-01 08:58:51.795  1459  1459 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@201c1dc1
07-01 08:58:51.795  1459  2197 I SocialFeedProvider: +onPause
07-01 08:58:51.795  1459  2197 I SocialFeedProvider: -onPause
,07-01 08:58:51.795   889  7193 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 08:58:51.795   889  7193 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1467356331814.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 08:58:51.795   889  7193 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:51.795   889  7193 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:51.795   889  7193 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:51.795   889  7193 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
07-01 08:58:51.795   889  7193 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:51.795   889  7193 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:51.795   889  7193 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:51.795   889  7193 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:51.795   889  7193 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:51.795   889  7193 E ErrorReport: 	... 4 more
,07-01 08:58:51.805   889   984 W ActivityManager: Can't addPackageDependency on system process
,07-01 08:58:51.825   889   990 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
07-01 08:58:51.825   889   990 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 08:58:51.825   889   990 D StatusBarManagerService: hiding MENU key,
,07-01 08:58:51.835   889  1511 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-01 08:58:51.835   889  1301 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
,07-01 08:58:51.855  1459  1459 I OrientationManager: [release],
07-01 08:58:51.855  1459  1459 I Prism.IndicatorPagedVi_: IndicatorPagedView.nCapability with type count = 1 and capability = 20
,07-01 08:58:51.885  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@14fa966 that was originally registered here. Are you missing a call to unregisterReceiver()?,
07-01 08:58:51.885  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@14fa966 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:689)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
,07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:51.885  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@23002bc that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.885  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@23002bc that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:153)
,07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:443)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.885  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@6bb95dd that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@6bb95dd that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	,at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1723)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:124)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:320)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.feed.local.calendar.CalendarFeedAdapter.<init>(CalendarFeedAdapter.java:97)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.feed.local.calendar.CalendarFeedProvider.onCreate(CalendarFeedProvider.java:19)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:152)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@7fbed54 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@7fbed54 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1723)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:124)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:698)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
,07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@980749e that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@980749e that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:333)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.feed.local.getstarted.GetStartedFeedProvider.onCreate(GetStartedFeedProvider.java:75)
07-01 08:58:51.895  1459  1459 E ActivityThread: ,	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:152)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@ac426cb that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@ac426cb that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
,07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:95)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:475)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@b8bd4fd that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@b8bd4fd that was originally registered here. Are you missing a call to unregisterReceiver()?
,07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:709)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@14a94287 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@14a94287 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	,at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:333)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:669)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	,at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:152)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@18dfd2c6 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@18dfd2c6 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:333)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:612)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:152)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,07-01 08:58:51.895  1459  1459 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@25588ea8 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@25588ea8 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1723)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:124)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:98)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:475)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	,at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@30c32689 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@30c32689 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:152)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:443)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	,at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:51.905  1459  1459 I OrientationManager: [init] currentOrienation: 1
07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@3e1cf5f2 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@3e1cf5f2 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495),
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:713)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:51.895  1459  1459 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@3f6c64a7 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@3f6c64a7 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:117)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:694)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:722)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1247)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6198)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1473)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1100(LauncherModel.java:1231)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1284)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:592)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:114)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:905)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:932)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1424)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:51.895  1459  1459 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:51.905   889  1667 W AppWidgetServiceImpl: startListening(),set useForground = true
07-01 08:58:51.905   889  1667 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1}
07-01 08:58:51.905   889  1667 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-01 08:58:51.905   889  1667 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1}
07-01 08:58:51.905   889  1667 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
,07-01 08:58:51.935   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,07-01 08:58:51.935   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 08:58:51.935   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:51.935   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,07-01 08:58:51.935   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted,
07-01 08:58:51.935   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
07-01 08:58:51.935   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
07-01 08:58:51.935   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:51.935   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,07-01 08:58:51.935   889   984 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=7194 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a,
07-01 08:58:51.935   889  1667 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider},
07-01 08:58:51.935   889  1667 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-01 08:58:51.935   889  1667 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
07-01 08:58:51.935   889  1667 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
,07-01 08:58:51.945  1459  1459 W ResourceType: Invalid package identifier when getting bag for resource number 0x00000014,
,07-01 08:58:51.945  1459  1459 I FeedScrollGridView: velocity 0.850000,
,07-01 08:58:51.955   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
07-01 08:58:51.955   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 08:58:51.955   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:51.955   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:51.955   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
07-01 08:58:51.955   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
07-01 08:58:51.955   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted,
07-01 08:58:51.955   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:51.955   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,07-01 08:58:51.965   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
07-01 08:58:51.965   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 08:58:51.965   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:51.965   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:51.965  1459  1459 I Prism.IndicatorPagedVi_: IndicatorPagedView.nCapability with type count = 1 and capability = 20
07-01 08:58:51.965   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
07-01 08:58:51.965   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
07-01 08:58:51.965   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,07-01 08:58:51.965   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:51.965   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,07-01 08:58:51.985   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,07-01 08:58:51.985   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 08:58:51.985   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:51.985   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:51.985   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
07-01 08:58:51.985   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
,07-01 08:58:51.985   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
07-01 08:58:51.985   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:51.985   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,07-01 08:58:52.005   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
07-01 08:58:52.005   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
,07-01 08:58:52.005   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:52.005   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:52.005   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
07-01 08:58:52.005   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
07-01 08:58:52.005   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,07-01 08:58:52.005   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:52.005   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,07-01 08:58:52.015  1397  1925 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,07-01 08:58:52.015  1397  1925 D PhoneApp: -- N1 =0
,07-01 08:58:52.015  1397  1925 D PhoneApp: -- N2 =0
07-01 08:58:52.015  1397  1925 D PhoneApp: -- N3 =0
,07-01 08:58:52.015   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,07-01 08:58:52.015   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 08:58:52.015   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:52.015   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:52.015   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
07-01 08:58:52.015   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
07-01 08:58:52.015   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
07-01 08:58:52.015   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:52.015   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,07-01 08:58:52.035   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
07-01 08:58:52.035   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 08:58:52.035   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:52.035   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,07-01 08:58:52.035   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
07-01 08:58:52.035   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
07-01 08:58:52.035   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
07-01 08:58:52.035   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:52.035   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,07-01 08:58:52.055   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,07-01 08:58:52.055   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 08:58:52.055   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:52.055   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:52.055   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,07-01 08:58:52.055   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
07-01 08:58:52.055   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
07-01 08:58:52.055   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:52.055   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,07-01 08:58:52.065   363   363 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,07-01 08:58:52.065   363   363 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-01 08:58:52.065   363   363 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-01 08:58:52.065   363   363 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,07-01 08:58:52.065   363   363 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
07-01 08:58:52.065   363   363 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=7
07-01 08:58:52.065   363   363 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,07-01 08:58:52.065   363   363 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
07-01 08:58:52.065   363   363 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!

```
