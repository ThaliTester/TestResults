#### Test 50650278ec2c976_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/art     ( 3043): Explicit concurrent mark sweep GC freed 19470(1057KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 2.028ms total 177.655ms
I/art     ( 4224): Explicit concurrent mark sweep GC freed 34304(2MB) AllocSpace objects, 22(440KB) LOS objects, 40% free, 20MB/34MB, paused 1.177ms total 107.823ms
I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 8211): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/System  ( 8211): core_booster, getBoosterConfig = false
I/System  ( 8211): core_booster, getBoosterConfig = false
I/qtaguid ( 8211): Failed write_ctrl(u 46) res=-1 errno=22
I/qtaguid ( 8211): Untagging socket 46 failed errno=-22
W/NetworkManagementSocketTagger( 8211): untagSocket(46) failed with errno -22
I/art     ( 2322): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 196us total 24.707ms
I/art     ( 2322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 216us total 23.500ms
I/art     ( 2322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 209us total 22.525ms
,I/qtaguid ( 8211): Failed write_ctrl(u 46) res=-1 errno=22
I/qtaguid ( 8211): Untagging socket 46 failed errno=-22
W/NetworkManagementSocketTagger( 8211): untagSocket(46) failed with errno -22
E/Thermal-daemon( 2329): [ap] temp_new :33  temp_old :34
I/art     ( 8211): Can not find class: Lorg/keyczar/i18n/messages_en_US;
I/art     ( 8211): Can not find class: Lorg/keyczar/i18n/messages_en;
I/art     ( 8211): Can not find class: Lorg/keyczar/i18n/messages;
I/MultiDex( 8349): VM with version 2.1.0 has multidex support
I/MultiDex( 8349): install
I/MultiDex( 8349): MultiDexExtractor.load(/data/app/com.google.android.gms-1/base.apk, false)
I/MultiDex( 8349): loading existing secondary dex files
I/MultiDex( 8349): load found 3 secondary dex files
I/MultiDex( 8349): install done
I/PG Utils( 8349): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/appproc ( 8370): CLASSPATH=/system/framework/am.jar
I/appproc ( 8370): Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
I/appproc ( 8370): app_process:number,5,0
I/AndroidRuntime( 8370): readDownloadBoosterConfig: 'false'
I/art     ( 8349): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
W/System  ( 8349): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c7038f3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8349): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 3043): filter receiver for action = com.google.android.gms.INITIALIZE
E/MDM     ( 4224): [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/GCoreFlp( 4224): No location to return for getLastLocation()
W/FusedLocationProvider( 4224): location=null
I/        ( 8370): power log dlsym ok
E/android_hardware_fm.cpp( 8370): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 8370): ========64bit long size = 8
E/FM_HAL  ( 8370): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 8370): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 8370): 
I/fm_hisi ( 8370): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 8370): 
I/fm_hisi ( 8370): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 8370): 
E/android_hardware_fm.cpp( 8370): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 3043): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 3043): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 3043): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 3043): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwSystemManager( 4448): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 4448): AppLockService:applock password not initial or function is closed
I/HwLauncher( 4197): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 4197): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 4197): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 4448): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 4197): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 4197): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/art     ( 8349): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
I/art     ( 8349): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8349): Can not find class: Lcom/google/android/gms/common/j/c;
I/art     ( 8349): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/WifiStateMachine( 3043):  ConnectedState what:131272 1 0
E/WifiStateMachine( 3043):  L2ConnectedState what:131272 1 0
E/WifiStateMachine( 3043):  ConnectModeState what:131272 1 0
E/WifiStateMachine( 3043):  DriverStartedState what:131272 1 0
E/WifiStateMachine( 3043):  SupplicantStartedState what:131272 1 0
E/WifiStateMachine( 3043):  DefaultState what:131272 1 0
E/WifiStateMachine( 3043): Error! unhandled message{ when=-4ms what=131272 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/PG Utils( 8349): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/WebViewFactory( 8401): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/LibraryLoader( 8401): Loading: webviewchromium
I/PG Utils( 8349): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/LibraryLoader( 8401): Time to load native libraries: 50 ms (timestamps 1654-1704)
I/LibraryLoader( 8401): Expected native library version number "",actual native library version number ""
I/PG Utils( 8349): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/LibraryLoader( 8401): Expected native library version number "",actual native library version number ""
I/chromium( 8401): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8401): Initializing chromium process, renderers=0
W/art     ( 8401): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 8401): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 8401): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 8401): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 8401): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 8401): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 8401): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/qtaguid ( 8211): Failed write_ctrl(u 46) res=-1 errno=22
I/qtaguid ( 8211): Untagging socket 46 failed errno=-22
W/NetworkManagementSocketTagger( 8211): untagSocket(46) failed with errno -22
W/art     ( 8401): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 8401): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 8401): Can not find class: Landroid/widget/ViewStub;
I/art     ( 8401): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 8401): Can not find class: Landroid/app/ViewStub;
W/art     ( 8401): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 8401): Attempt to remove local handle scope entry from IRT, ignoring
I/PhoneStatusBar( 3710): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/PhoneStatusBar( 3710): shouldTranslucent:true
I/PhoneStatusBar( 3710): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/OpenGLRenderer( 8401): Initialized EGL, version 1.4
,I/ActivityManager( 3043): Displayed com.test.thalitest/.MainActivity: +1s39ms (total +1s116ms)
W/IInputConnectionWrapper( 8401): showStatusIcon on inactive InputConnection
,I/chromium( 8401): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 8401): 
,I/PG Utils( 8211): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 8211): core_booster, getBoosterConfig = false
,I/System  ( 8211): core_booster, getBoosterConfig = false
,W/jxcore-log( 8401): Initializing JXcore engine
W/jxcore-log( 8401): JXcore engine is ready
,W/jxcore-log( 8401): Starting JXcore engine
,W/jxcore-log( 8401): Platform android
W/jxcore-log( 8401): 
W/jxcore-log( 8401): Process ARCH arm
W/jxcore-log( 8401): 
,I/art     ( 3043): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/jxcore-log( 8401): JXcore Cordova bridge is ready!
I/jxcore-log( 8401): 
W/jxcore-log( 8401): JXcore engine is started
,I/HwSystemManager( 4448): HoldService:uid:10044 pid:8117 died
I/HwSystemManager( 4448): HoldService:oldVersionKey:10044,8117
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10044
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10044, pid: 8117
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10044, pid: 8117
,I/jxcore-log( 8401): Toggling radios to true
I/jxcore-log( 8401): 
,I/HwSystemManager( 4448): HoldService:checkBeforeShowDialog: uid:10295 pid:8401, permissionType:2097152
I/HwSystemManager( 4448): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 3043): allowOpenWifi blocked:false
,E/WifiStateMachine( 3043):  ConnectedState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState CMD_DISCONNECT 0 0
,E/WifiNative: ( 3043): [106,302,819 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
,I/jxcore-log( 8401): Radios toggled
I/jxcore-log( 8401): 
I/wpa_supplicant( 3815): set current WIFI status to BT!
I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
,I/wpa_supplicant( 3815): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,W/wpa_supplicant( 3815): check_associate_result func start
,I/jxcore-log( 8401): Got Device Bluetooth address: 58:2A:F7:ED:96:BE
I/jxcore-log( 8401): 
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 3043): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/jxcore-log( 8401): Perf Test app loaded loaded
I/jxcore-log( 8401): 
,W/System.err( 3043): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3043): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3043): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3043): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3043): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3043): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 3043): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 3043): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 3043): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 3043): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 3043): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 3043): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 3043): This is not beta user build
,I/jxcore-log( 8401): check test folder
I/jxcore-log( 8401): 
,I/jxcore-log( 8401): found test : ./testFindPeers.js
I/jxcore-log( 8401): 
,W/wpa_supplicant( 3815): STA MODE: Set shutdown wlan cmd SUCCESS
,W/wpa_supplicant( 3815): check_associate_result func start
,E/WifiStateMachine( 3043): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 3043): setScanAlarm false period 20000 initial delay 0
,E/WifiStateMachine( 3043): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 3043): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3043): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/wpa_supplicant( 3815): set current WIFI status to BT!
,I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
E/WifiMonitor( 3043): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/jxcore-log( 8401): found test : ./testSendData.js
I/jxcore-log( 8401): 
,E/native  ( 3043): do suspend true
,I/wpa_supplicant( 3815): set current WIFI status to BT!
,I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/ArpVerifier( 3043): current SSID is empty.
,I/ActivityManager( 3043): filter receiver for action = com.google.android.gcm.DISCONNECTED
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 3043): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3043):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=false
,E/WifiStateMachine( 3043): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 3043):  DisconnectingState CMD_RECONNECT 0 0
,E/WifiStateMachine( 3043):  ConnectModeState CMD_RECONNECT 0 0
,E/WifiNative: ( 3043): [106,446,911 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
,W/wpa_supplicant( 3815): check_associate_result func start
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/wpa_supplicant( 3815): wlan is down..., now start up...
,E/WifiStateMachine( 3043):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106461
,E/WifiStateMachine( 3043):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106462
,E/native  ( 3043): do suspend true
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
W/View    ( 3710): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{3340f7ac V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3710): STATE =1
,W/wpa_supplicant( 3815): STA MODE: Open wlan cmd SUCCEESS
I/wpa_supplicant( 3815): set current WIFI status to BT!
,I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 5698): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 5698): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,I/wpa_supplicant( 3815): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3043): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 3043): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3815): set current WIFI status to BT!
I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
,I/art     ( 3043): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE,
E/WifiStateMachine( 3043):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=false
,E/WifiStateMachine( 3043): setScanAlarm true period 0 initial delay 200,
E/WifiStateMachine( 3043):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=107233  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 3043): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3043):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=107234  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/Choreographer( 8401): Skipped 150 frames!  The application may be doing too much work on its main thread.,
,I/HwSystemManager( 4448): aor:Network Stats Updated,
I/HwSystemManager( 4448): aoi:onNetworkStatsUpdated
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiStateMachine( 3043):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3043):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,I/HwSystemManager( 4448): aor:Network Stats Updated
I/HwSystemManager( 4448): aoi:onNetworkStatsUpdated
E/WifiStateMachine( 3043):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3043):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES,
,E/WifiStateMachine( 3043):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=107256  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,E/WifiStateMachine( 3043): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false,
I/chromium( 8401): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE,
E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.,
I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
E/HwSystemManager( 4448): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/WifiStateMachine( 3043):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=107268  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null,
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4448): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/chromium( 8401): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4448): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4448): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4448): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,E/HwSystemManager( 4448): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,I/WifiTracker( 3710): STATE =1
,I/wpa_supplicant( 3815): set current WIFI status to BT!
,I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: wlan common protect cancelled, nothing to do
,E/WifiMonitor( 3043): handleEvent 12  CTRL-EVENT-BSS-ADDED 3 06:7c:34:12:7f:81
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 3043): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 3043): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 3043):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:57 bcn=0
E/WifiStateMachine( 3043):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:57 bcn=0
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=36 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine( 3043):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:57 bcn=0
,I/wpa_supplicant( 3815): Trying to associate with c0:**:**:**:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine( 3043):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:57 bcn=0
E/WifiStateMachine( 3043): [1,450,109,368,893 ms] noteScanEnd no scan source
W/wpa_supplicant( 3815): check_associate_result func start
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,I/wpa_supplicant( 3815): set current WIFI status to BT!,
,I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
,I/bluetooth-coex( 5698): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 5698): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 5698): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
,E/WifiStateMachine( 3043): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3fa9390a sup_state=SCANNING debouncing=false
E/WifiAutoJoinController ( 3043): NG700 c0:ff:d4:d3:aa:48 rssi=-60 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,E/WifiAutoJoinController ( 3043): 01ABC c2:ff:d4:d3:aa:48 rssi=-67 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController ( 3043): Gonzos 38:f8:89:11:e9:11 rssi=-89 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController ( 3043): UPC Wi-Free 06:7c:34:12:7f:81 rssi=-93 cap [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController ( 3043): ageScanResultsOut delay 40000 size 4 now 1450109368900
E/WifiAutoJoinController ( 3043): newSupplicantResults size=4 known=1 true
,E/WifiAutoJoinController ( 3043): attemptAutoJoin() status=wpa_state=ASSOCIATING
,E/WifiAutoJoinController ( 3043): p2p_device_address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 3043): address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 3043): uuid=fc3e6a12-87ef-50cc-87ec-720c7386849f split=4
E/WifiAutoJoinController ( 3043): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiStateMachine( 3043):  DisconnectedState CMD_TARGET_BSSID 36 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107840
,E/WifiStateMachine( 3043):  ConnectModeState CMD_TARGET_BSSID 36 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107841
E/WifiStateMachine( 3043):  DriverStartedState CMD_TARGET_BSSID 36 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107841
,E/WifiStateMachine( 3043):  SupplicantStartedState CMD_TARGET_BSSID 36 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107841
E/WifiStateMachine( 3043):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=107842  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 3043): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE,
,E/WifiStateMachine( 3043):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=107849  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,E/HI110X_CHR_LOGD( 2735): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory,
W/wpa_supplicant( 3815): check_associate_result func start
I/wpa_supplicant( 3815): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=39 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 3043):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=108510  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 3043): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3043):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=108512  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 3043): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72 SSID=0x
,E/WifiStateMachine( 3043):  DisconnectedState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=108523
,E/WifiStateMachine( 3043):  ConnectModeState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=108523
,E/WifiStateMachine( 3043):  DriverStartedState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=108524
E/WifiStateMachine( 3043):  SupplicantStartedState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=108524
,E/WifiStateMachine( 3043):  DefaultState CMD_ASSOCIATED_BSSID 39 0 BSSID=c0:ff:d4:d3:aa:48 Target=c0:ff:d4:d3:aa:48 roam=0 rt=108525
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,W/ArpVerifier( 3043): ignore msg MSG_CHECK_WIFI_STATE, msg token = 4, expected token = 8
,I/ActivityManager( 3043): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 4169): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 4169): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 4169): bBrokenPipe = false
,I/ActivityManager( 3043): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/HwEmailTag( 7380): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7380): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7380): EmailProvider->notifyNetworkChanged->
,I/SUPL20_SCM( 4169): Network connection true
,I/SUPL20_SPIMESLP-SENDING( 4169): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 4169): bBrokenPipe = false
,E/TEST-APN( 4143): query for APN: check-permission succ 
E/TEST-APN( 4143): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3043): No APN found to select.
,W/View    ( 3710): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{3340f7ac V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
W/GNSS_ADAPTER( 3043): This function not used.
W/GNSS_ADAPTER( 3043): This function not used.
,E/TEST-APN( 4143): query for APN: check-permission succ 
E/TEST-APN( 4143): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,E/GpsLocationProvider( 3043): No APN found to select.
,W/GNSS_ADAPTER( 3043): This function not used.
W/GNSS_ADAPTER( 3043): This function not used.
,I/DownloadManager( 3686): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/HwCust  ( 7894): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
,I/MagazineUtils( 3598): is magazine unlock on, now is lock screen diabled mode
I/HwCust  ( 7894): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
,I/Mms_TXM_SVC( 7894): onStartCommand send EVENT_NEW_INTENT. service-id 1
,W/Mms_TXM_SVC( 7894): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,E/HwOUC   ( 8499): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 8499): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 8499): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 8499): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 8499): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 8499): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 8499): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8499): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/HwSystemManager( 4448): HoldService:uid:10004 pid:7434 died
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10004
I/HwSystemManager( 4448): HoldService:oldVersionKey:10004,7434
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10004, pid: 7434
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10004, pid: 7434
,W/asset   ( 8522): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 8522): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/HwSystemManager( 4448): HoldService:uid:10050 pid:8280 died
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 4448): HoldService:oldVersionKey:10050,8280
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10050, pid: 8280
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10050, pid: 8280
,W/asset   ( 8544): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwCust  ( 8544): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,E/HwSystemManager( 7552): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwSystemManager( 4448): HoldService:uid:10086 pid:7673 died
I/HwSystemManager( 4448): HoldService:oldVersionKey:10086,7673
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10086
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10086, pid: 7673
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10086, pid: 7673
,W/SQLiteConnectionPool( 6675): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/Thermal-daemon( 2329): [charger_ic] temp_new :32  temp_old :33
,I/jxcore-log( 8401): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 8401): 
,E/WifiStateMachine( 3043):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 3043):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3043):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 3043):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 3043):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,W/wpa_supplicant( 3815): check_associate_result func start
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3043):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=111521  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 3043): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3043):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=111526  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/wpa_supplicant( 3815): check_associate_result func start
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
W/wpa_supplicant( 3815): check_associate_result func start
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3043):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=111533  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 3043): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3043):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=111534  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=42 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 3043): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3815): WPA: Key negotiation completed with c0:**:**:**:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3815): set current WIFI status to BT!
I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: BT_COEX_PAUSE cancel
I/wpa_supplicant( 3815): set current WIFI status to BT!
I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: BT_COEX_CHANNEL, fist[0]last[23]afh_result[0]
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
E/WifiMonitor( 3043): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3815): CTRL-EVENT-CONNECTED - Connection to c0:**:**:**:aa:48 completed (auth) [id=0 id_str=]
W/wpa_supplicant( 3815): check_associate_result func start
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3043):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111542
E/WifiStateMachine( 3043):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111542
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
W/System.err( 3043): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3043): ,	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3043): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3043): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3043): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
,W/System.err( 3043): 	at com.android.server.wifi.WifiStateMachine$ConnectModeState.processMessage(WifiStateMachine.java:7299)
W/System.err( 3043): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/System.err( 3043): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/System.err( 3043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3043): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3043): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ReportTools( 3043): This is not beta user build
I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3043): setScanAlarm false period 0 initial delay 0
I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3043): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 3043): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3043): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WiFi_PRO( 3043): obtaining wifi is conencted
,I/WiFi_PRO( 3043): obtaining wifi is conencted
,E/WifiStateMachine( 3043): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3043): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3043): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,E/WifiStateMachine( 3043): Start Dhcp Watchdog 2
,E/WifiStateMachine( 3043):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=111586  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 3043):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=111587  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 3043):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=111587  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 3043):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3043):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 3043):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,I/wpa_supplicant( 3815): set current WIFI status to BT!
I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: get dhcp start, wait for complete msg
,E/native  ( 3043): do suspend false
,E/WifiStateMachine( 3043): Unexpected BatchedScanResults :OK
,E/WifiStateMachine( 3043): noteBatchedScanstop()
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,I/WifiTracker( 3710): STATE =1
,I/WifiTracker( 3710): STATE =1
,I/WifiTracker( 3710): STATE =1
,I/DHCPCD  ( 8595): version 5.5.6 starting
,W/DHCPCD  ( 8595): hw_parse_xidfile 
I/DHCPCD  ( 8595): wlan0: dhcp start reboot
I/DHCPCD  ( 8595): wlan0: rebinding lease of 192.168.1.120
,I/HwSystemManager( 4448): HoldService:uid:10026 pid:8158 died
I/HwSystemManager( 4448): HoldService:oldVersionKey:10026,8158
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10026, pid: 8158
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10026, pid: 8158
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10026
,I/DHCPCD  ( 8595): wlan0: dhcp ack, acknowledged 192.168.1.120 from 192.168.1.1
,W/ContextImpl( 8602): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 8602): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/ContextImpl( 8602): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 8602): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8602): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8602):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8602):   adb logcat -s GAv4
,I/DHCPCD  ( 8595): wlan0: checking for 192.168.1.120
,W/GAv4    ( 8602): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8602): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8602): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/HwEmailTag( 7380): EmailProvider->handleNetworkChanged->network is bad, WON'T start new EmailConnectivityTask
I/HwEmailTag( 7380): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7380): EmailProvider->triggerPeroidSync->accountId:-1
,E/WifiStateMachine( 3043):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/art     ( 3043): Explicit concurrent mark sweep GC freed 57103(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.976ms total 188.583ms
,I/PG Utils( 8602): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/DHCPCD  ( 8595): wlan0: leased 192.168.1.120 for 86400 seconds
,E/WifiStateMachine( 3043):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3043):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3043): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/art     ( 8602): Can not find class: Ljava/util/ConcurrentNavigableMap;
,I/WebViewFactory( 8602): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 8602): Loading: webviewchromium
,I/LibraryLoader( 8602): Time to load native libraries: 4 ms (timestamps 3987-3991)
,I/LibraryLoader( 8602): Expected native library version number "",actual native library version number ""
,I/LibraryLoader( 8602): Expected native library version number "",actual native library version number ""
,I/chromium( 8602): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8602): Initializing chromium process, renderers=0
,W/art     ( 8602): Attempt to remove local handle scope entry from IRT, ignoring
,E/WifiStateMachine( 3043):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 3043):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/native  ( 3043): do suspend true
,I/wpa_supplicant( 3815): set current WIFI status to BT!
I/bluetooth-coex( 5698): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5698): set_bt_coex_mode_ext: get dhcp done, stop timer during reserved time
,E/WifiStateMachine( 3043): wifistatemachine handleIPv4Success <IP address 192.168.1.120/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine( 3043): link address 192.168.1.120/24
,E/WifiStateMachine( 3043): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3043): updateWifiIp  StateMachine 192.168.1.120
,E/WifiStateMachine( 3043):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,W/chromium( 8602): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 8602): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
I/chromium( 8602): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3043): filter receiver for action = android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 3043): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
,E/WifiStateMachine( 3043): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,W/AudioManagerAndroid( 8602): Requires BLUETOOTH permission
,E/WifiStateMachine( 3043): updateDefaultRouteMacAddress reachable (tried again) :192.168.1.1 found c0:ff:d4:d3:aa:48
,I/HwSystemManager( 4448): aor:Network Stats Updated
I/HwSystemManager( 4448): aoi:onNetworkStatsUpdated
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4448): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4448): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 4448): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 4448): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 4448): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 4448): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 4448): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/NSApplication( 8602): Starting up...
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,I/System  ( 3043): core_booster, getBoosterConfig = false
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,E/WifiStateMachine( 3043):  ConnectedState CMD_UNWANTED_NETWORK 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=0 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:31467] from screen [on:0 period:-1589570674] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,I/HwSystemManager( 4448): HoldService:uid:10032 pid:7789 died
I/HwSystemManager( 4448): HoldService:oldVersionKey:10032,7789
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10032
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10032, pid: 7789
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10032, pid: 7789
,I/NetworkSpeedManagerEx( 3710): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3710): wifiManager = android.net.wifi.WifiManager@2188bbb7
,I/NetworkSpeedManagerEx( 3710): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = true, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3710): stop
,I/WifiTracker( 3710): STATE =1
,W/View    ( 3710): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{3340f7ac V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/WifiTracker( 3710): STATE =1
,I/WifiTracker( 3710): STATE =1
,W/View    ( 3710): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{3340f7ac V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 5
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=45 dispatchEvent: HEART-BEAT-ACK: 5
E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/PG Utils( 8690): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3043): broadcastpkg:[com.google.android.apps.plus] pid:[null]  maybe timeout , send to PG
,I/HwCust  ( 8716): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl
,I/HwSystemManager( 4448): HoldService:uid:10040 pid:7272 died
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/HwSystemManager( 4448): HoldService:oldVersionKey:10040,7272
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10040, pid: 7272
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10040, pid: 7272
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10040
,I/PG Utils( 8716): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7380): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7380): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7380): EmailProvider->notifyNetworkChanged->
,I/System  ( 7704): core_booster, getBoosterConfig = false
,I/HwCust  ( 8716): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
,I/HwCust  ( 8716): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
,I/DownloadManager( 3686): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/HwCust  ( 8716): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
,I/Mms_TXM_SVC( 7894): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7894): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/MagazineUtils( 3598): is magazine unlock on, now is lock screen diabled mode
,E/ContactsProtector( 8716): getHiCloudAccountData query fail
,I/HwOUC   ( 8499): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8499): [main-1]Network not available(hwouc/DownloadReceiver.java:195)
,I/PG Utils( 8690): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/art     ( 8522): Can not find class: Landroid/provider/Settings$Systemex;
E/HwThemeManager( 8522): ThemeHelperretry to get Settings
,E/HwSystemManager( 7552): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/art     ( 4143): Explicit concurrent mark sweep GC freed 26878(1432KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.388ms total 80.917ms
,I/HwCust  ( 8716): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
,I/HwCust  ( 8716): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
,I/HwSystemManager( 4448): ContactsObserverHelper:Receive contacts change broadcast
,I/PG Utils( 8211): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 8211): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 8211): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 8211): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ElegantRequestDirector( 8211): I/O exception (javax.net.ssl.SSLException) caught when processing request: Write error: ssl=0x5599c30de0: I/O error during system call, Broken pipe
,I/ElegantRequestDirector( 8211): Retrying request
,W/ArpVerifier( 3043): ignore msg MSG_CHECK_WIFI_STATE, msg token = 9, expected token = 10
,I/ActivityManager( 3043): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE
,I/SUPL20_SCM( 4169): Network connection true
,I/AccountTypeManager( 7894): Adding account type = com.android.contacts.model.account.ExchangeAccountType@2e40c4c9 in the cache
,I/SUPL20_SPIMESLP-SENDING( 4169): m_bPacket.length 8
I/SUPL20_SPIMESLP-SENDING( 4169): bBrokenPipe = false
,I/NetworkMonitor( 7937): type=WIFI subType= reason=null isConnected=true
,I/HwEmailTag( 7380): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
I/HwEmailTag( 7380): HwUtils->notifyNetworkChanged->
I/HwEmailTag( 7380): EmailProvider->notifyNetworkChanged->
,I/SimFactoryManager( 7894): Get SIM state from SIM factory manager: 1,For slotId:0
,E/TEST-APN( 4143): query for APN: check-permission succ 
E/TEST-APN( 4143): Telephony query SQL: SELECT apn FROM carriers WHERE (_id = -1)
,I/SimFactoryManager( 7894): Get SIM state from SIM factory manager: 1,For slotId:1
,E/GpsLocationProvider( 3043): No APN found to select.
,I/System  ( 8211): core_booster, getBoosterConfig = false
W/GNSS_ADAPTER( 3043): This function not used.
W/GNSS_ADAPTER( 3043): This function not used.
,I/AccountTypeManager( 7894): Adding account type = com.android.contacts.model.account.ExternalAccountType@29ff37ce in the cache
,I/DownloadManager( 3686): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/System  ( 8211): core_booster, getBoosterConfig = false
,W/ResourceType( 7894): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 7894): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 7894): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 7894): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 7894): Adding account type = com.android.contacts.model.account.ExternalAccountType@9bad30b in the cache
,I/AccountTypeManager( 7894): Adding account type = com.android.contacts.model.account.GoogleAccountType@165b65e8 in the cache
,I/MagazineUtils( 3598): is magazine unlock on, now is lock screen diabled mode
I/Mms_TXM_SVC( 7894): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 7894): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,I/HwOUC   ( 8499): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 8499): [main-1]Network available(hwouc/DownloadReceiver.java:142)
,I/HwOUC   ( 8499): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
,I/HwOUC   ( 8499): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
,I/HwOUC   ( 8499): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
,E/ExternalAccountType( 7894): Unsupported attribute readOnly
,I/art     ( 8522): Can not find class: Landroid/provider/Settings$Systemex;
E/HwThemeManager( 8522): ThemeHelperretry to get Settings
,I/AccountTypeManager( 7894): AccountManager, account size is: 2
,I/HwOUC   ( 8499): [Thread-129-129]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995)
,I/AccountTypeManager( 7894): Loaded meta-data for 5 account types, 3 accounts in 75ms(wall) 35ms(cpu)
,E/HwSystemManager( 7552): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/HwOUC   ( 8499): [Thread-129-129]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
,I/Process ( 8499): Sending signal. PID: 8499 SIG: 9
,E/WifiStateMachine( 3043):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 3043):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 3043):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,I/HwSystemManager( 4448): HoldService:uid:10052 pid:8499 died
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/HwSystemManager( 4448): HoldService:oldVersionKey:10052,8499
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10052, pid: 8499
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10052
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10052, pid: 8499
,E/Thermal-daemon( 2329): [ap] temp_new :32  temp_old :33
,W/SyncManager( 3043): SyncManager manageSyncAlarmLocked SET_WAKE_ALARM
,I/HwEmailTag( 7380): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
I/HwEmailTag( 7380): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7380): EmailProvider->triggerPeroidSync->accountId:-1
I/HwEmailTag( 7380): EmailConnectivityTask->syncOutbox
I/HwEmailTag( 7380): EmailProvider->query->1450109381158;end;;consuming:5ms;
,W/ArpVerifier( 3043): ignore msg MSG_CHECK_WIFI_STATE, msg token = 3, expected token = 10
,I/HwSystemManager( 4448): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4448): BgPowerManagerService: mTimes = 30092 firstTime = 92721 firstmBatteryCapacity =2203
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/playlog/OneTimePlayLogger;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/playlog/PlayLogger$LoggerCallbacks;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/playlog/PlayLogger;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/playlog/internal/PlayLoggerImpl;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/playlog/internal/PlayLoggerContext;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/playlog/internal/LogEvent;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/playlog/internal/IPlayLogService;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/playlog/internal/LoggerConnectionCallbacks;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient$ConnectionCallbacks;
,I/art     ( 6675): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient$OnConnectionFailedListener;
,I/HwSystemManager( 4448): ContactsObserverHelper:onContactsChanged: Start to handle contacts change message
,I/HwSystemManager( 4448): bbe:onPreContactsChange: Starts
,I/HwSystemManager( 4448): ContactsObserver:onPreContactsChange: Starts
,I/HwSystemManager( 4448): ContactsObserver:loadLocalContacts: No contacts
,I/PG Utils( 4448): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 4448): ContactsObserverHelper:applyContactsUpdate: Starts
I/HwSystemManager( 4448): bbe:onContactsChange: Starts
I/HwSystemManager( 4448): ContactsObserverHelper:applyContactsUpdate: Ends
,I/HwSystemManager( 4448): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4448): BgPowerManagerService: mTimes = 33796 firstTime = 92721 firstmBatteryCapacity =2203
,I/art     ( 8522): System.exit called, status: 0
I/AndroidRuntime( 8522): VM exiting with result code 0, cleanup skipped.
,I/HwSystemManager( 4448): HoldService:uid:10060 pid:8522 died
I/HwSystemManager( 4448): HoldService:oldVersionKey:10060,8522
I/HwSystemManager( 4448): BgPowerManagerService:onProcessDied uid = 10060
E/HsmCoreServiceImpl( 3043): onTransact in code is: 102
I/MediaProcessHandler( 3043): processOp opType: 1, uid: 10060, pid: 8522
W/MediaProcessHandler( 3043): remove target not exist, maybe the UI process: uid: 10060, pid: 8522
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 6
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=46 dispatchEvent: HEART-BEAT-ACK: 6
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2329): [charger_ic] temp_new :31  temp_old :32
,E/Thermal-daemon( 2329): [ap] temp_new :31  temp_old :32
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 7
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=47 dispatchEvent: HEART-BEAT-ACK: 7
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/PG Utils( 6675): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6675): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,W/IcingInternalCorpora( 6675): getNumBytesRead when not calculated.
,I/HwSystemManager( 4448): InputMethodStringPredicate:InputMethodStringPredicate :: inputMethods = [com.nuance.swype.emui, com.nuance.swype.input.HuaweiIME, com.android.inputmethod.latin]
,I/HwSystemManager( 4448): LauncherPredicate:get default launcher is null, set hwlauncher
,I/HwSystemManager( 4448): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4448): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4448): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4448): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4448): SmartMemoryCleanService:Smcs provider called method:execSQLS
,W/HwSystemManager( 4448): HsmContentProvider:call: Unknown call method = execSQLS
,I/HwSystemManager( 4448): SmartMemoryCleanService:SMCSDataManager.checkAvailMemory.: availMem 1030004736 [332800000,437657600,542515200]
I/HwSystemManager( 4448): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor start
,I/HwSystemManager( 4448): SmartMemoryCleanService:SMCSControl.handleSMCSTimerOut call startCPUMeMMonitor end
,E/WifiStateMachine( 3043):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3043):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 3043):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 3043):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 3043):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 3043):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/HwSystemManager( 4448): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4448): BgPowerManagerService: mTimes = 60172 firstTime = 92721 firstmBatteryCapacity =2203
,I/ActivityManager( 3043): filter receiver for action = com.google.android.gms.gcm.ACTION_CHECK_QUEUE
,I/ActivityManager( 3043): filter receiver for action = android.bluetooth.intent.DISCOVERABLE_TIMEOUT
,I/HwLauncher( 4197): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3710): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3710): hand message 1
I/TimeManager( 3710): notify time change. size = 2
,I/TimeLayout( 3710): time = 17:10
,I/TimeLayout( 3710): updateDate date = 12/14/2015
,I/TimeLayout( 3710): weekDay = Monday
,I/bluedroid( 5698): bt interface: [set_adapter_property]
I/bluedroid( 5698): bt interface: [set_adapter_property]
W/bt-btif ( 5698): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btm  ( 5698): BTM_SetDiscoverability
I/BluetoothAdapterProperties( 5698): adapterPropertyChangedCallback with type:9 len:4
W/bt-btm  ( 5698): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-btif ( 5698): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 5698): adapterPropertyChangedCallback with type:7 len:4
,I/VacuumService( 4224): Vacuum at: now=1450109419900 tag=VacuumService
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 3043): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeConfigurator( 4224): Scheduling Phenotype for one-off execution 8108 seconds from now (1450109420223)
,I/art     ( 3043): Explicit concurrent mark sweep GC freed 53386(3MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 2.077ms total 192.841ms
I/ActivityManager( 3043): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 6675): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PhenotypeFlagCommitter( 4224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GoogleURLConnFactory( 4224): Using platform SSLCertificateSocketFactory
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 4224): core_booster, getBoosterConfig = false
,I/System  ( 4224): core_booster, getBoosterConfig = false
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 8
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=48 dispatchEvent: HEART-BEAT-ACK: 8
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/PG Utils( 4224): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Thermal-daemon( 2329): [ap] temp_new :30  temp_old :31
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 9
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=49 dispatchEvent: HEART-BEAT-ACK: 9
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2329): [charger_ic] temp_new :30  temp_old :31
,I/OAM     ( 2734): [check_file_size:402]/data/hwlogdir/wifi_log/wifi_log_1 log file beyond size=10240Byte, creat new file
I/OAM     ( 2734): [rename_old_file:107]rename_old_file
I/OAM     ( 2734): 
,I/HwSystemManager( 4448): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4448): BgPowerManagerService: mTimes = 93799 firstTime = 92721 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 10
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=50 dispatchEvent: HEART-BEAT-ACK: 10
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 11
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=51 dispatchEvent: HEART-BEAT-ACK: 11
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4448): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4448): BgPowerManagerService: mTimes = 120333 firstTime = 92721 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 12
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=52 dispatchEvent: HEART-BEAT-ACK: 12
E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/ClearcutLoggerApiImpl( 4224): disconnect managed GoogleApiClient
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 13
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=53 dispatchEvent: HEART-BEAT-ACK: 13
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 14
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=54 dispatchEvent: HEART-BEAT-ACK: 14
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
E/WifiMonitor( 3043): handleEvent 13  CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 15
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=56 dispatchEvent: HEART-BEAT-ACK: 15
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4448): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4448): BgPowerManagerService: mTimes = 180492 firstTime = 92721 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 16
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=57 dispatchEvent: HEART-BEAT-ACK: 16
E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,E/Thermal-daemon( 2329): [ap] temp_new :29  temp_old :30
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 3043): handleEvent 13  CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81
E/WifiMonitor( 3043): handleEvent 13  CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 17
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=60 dispatchEvent: HEART-BEAT-ACK: 17
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0
,I/HwSystemManager( 4448): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4448): BgPowerManagerService: mTimes = 210578 firstTime = 92721 firstmBatteryCapacity =2203
,I/HwSystemManager( 4448): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 4448): BgPowerManagerService: mTimes = 213800 firstTime = 92721 firstmBatteryCapacity =2203
,I/wpa_supplicant( 3815): wlan0: HEART-BEAT-ACK: 18
,E/WifiMonitor( 3043): WifiMonitor:wlan0 cnt=61 dispatchEvent: HEART-BEAT-ACK: 18
,E/WifiStateMachine( 3043):  ConnectedState what:147506 0 0
E/WifiStateMachine( 3043):  L2ConnectedState what:147506 0 0
,E/WifiStateMachine( 3043):  ConnectModeState what:147506 0 0
,E/WifiStateMachine( 3043):  DriverStartedState what:147506 0 0
,E/WifiStateMachine( 3043):  SupplicantStartedState what:147506 0 0

```
