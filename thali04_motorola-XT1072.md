#### Test 50650278d1b06e8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
D/AndroidRuntime( 6406): 
D/AndroidRuntime( 6406): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6406): CheckJNI is OFF
D/AndroidRuntime( 6406): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6425 uid=10397 gids={50397, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6406): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6425): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6425): Time to load native libraries: 3 ms (timestamps 7416-7419)
,I/LibraryLoader( 6425): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6425): Binding Chromium to main looper Looper (main, tid 1) {24760d0a}
,I/LibraryLoader( 6425): Expected native library version number "",actual native library version number ""
,I/chromium( 6425): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6425): Initializing chromium process, singleProcess=true
,W/art     ( 6425): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6425): ApplicationContext is null in ApplicationStatus
,W/chromium( 6425): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6425): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6425): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6425): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6425): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6425): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6425): Local Branch: 
I/Adreno-EGL( 6425): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6425): Local Patches: NONE
I/Adreno-EGL( 6425): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
,D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39cf50a4:true
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{e2aac99 u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6425): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6425): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6425): CordovaWebView is running on device made by: motorola
,W/art     ( 6425): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6425): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6425): Render dirty regions requested: true
,D/Atlas   ( 6425): Validating map...
,W/chromium( 6425): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  880): Explicit concurrent mark sweep GC freed 28248(1392KB) AllocSpace objects, 2(224KB) LOS objects, 33% free, 20MB/30MB, paused 1.411ms total 125.744ms
,I/OpenGLRenderer( 6425): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6425): Enabling debug mode 0
,I/Keyboard.Facilitator( 1418): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1082
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +994ms (total +1s82ms)
,W/IInputConnectionWrapper( 6425): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6425): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6425): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6425): Cannot call determinedVisibility() - never saw a connection for the pid: 6425
,D/JsMessageQueue( 6425): Set native->JS mode to OnlineEventsBridgeMode
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/jxcore_app_log( 6425): JniHelper::setJavaVM(0xb7e67310), pthread_self() = -1205899912
D/JX-Cordova( 6425): jxcore cordova android initializing
,W/jxcore-log( 6425): Initializing JXcore engine
W/jxcore-log( 6425): JXcore engine is ready
,W/jxcore-log( 6425): Starting JXcore engine
,W/.test.thalitest( 6425): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10397 path="socket:[5651]" dev="sockfs" ino=5651 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6425): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10397 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6425): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10397 path="socket:[6778]" dev="sockfs" ino=6778 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6425): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10397 path="socket:[26798]" dev="sockfs" ino=26798 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6425): Platform android
W/jxcore-log( 6425): 
,W/jxcore-log( 6425): Process ARCH arm
W/jxcore-log( 6425): 
,I/jxcore-log( 6425): JXcore Cordova bridge is ready!
I/jxcore-log( 6425): 
,W/jxcore-log( 6425): JXcore engine is started
,I/Choreographer( 6425): Skipped 181 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6425): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312240, SEQNUM=4416, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-356, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/jxcore-log( 6425): Toggling radios to true
I/jxcore-log( 6425): 
,D/BluetoothAdapter( 6425): enable(): BT is already enabled..!
,D/WifiService(  880): setWifiEnabled: true pid=6425, uid=10397
D/WifiService(  880): New client listening to asynchronous messages
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6425): Radios toggled
I/jxcore-log( 6425): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6425): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6425): 
I/jxcore-log( 6425): Perf Test app loaded loaded
I/jxcore-log( 6425): 
,I/jxcore-log( 6425): check test folder
I/jxcore-log( 6425): 
I/jxcore-log( 6425): found test : ./testFindPeers.js
I/jxcore-log( 6425): 
,I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  291):  STA Disconnected !!
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  466): NL - Read 1004 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  291): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering(  880): InitialState.processMessage what=4
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  291): Event received = CTRL-EVENT-REGDOM-CHANGE
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880):  0
,I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  291): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService(  880): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  288): Clearing all IP addresses on wlan0
D/TCMD    (  466): NL - Read 60 bytes from update socket.
D/TCMD    (  466): NL - ignore NL message, type = 21
D/TCMD    (  466): Listening for incoming client connection request
,V/NativeCrypto( 1833): Read error: ssl=0xb8067498: I/O error during system call, Connection timed out
V/NativeCrypto( 1833): SSL shutdown failed: ssl=0xb8067498: I/O error during system call, Broken pipe
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/jxcore-log( 6425): found test : ./testSendData.js
I/jxcore-log( 6425): 
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  880): connected time updated 113984
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6493 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524292
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
,I/jxcore-log( 6425): found test : ./testSendData2.js
I/jxcore-log( 6425): 
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/jxcore  ( 6425): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 6425): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/chromium( 6425): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  288): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6493): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6523 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6258:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_6258/cgroup.procs: No such file or directory
,W/ResourcesManager( 6523): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1833): Scheduling Phenotype for one-off execution 5641 seconds from now (1450655589521)
,D/GetConfigurationSnapshotOperation( 1833): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1833): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1833): Using platform SSLCertificateSocketFactory
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  291): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  466): NL - Read 56 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,I/wpa_supplicant( 1439): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  291): Event received = Trying to associate with
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  880): [1,450,655,589,630 ms] noteScanEnd no scan source
D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1439): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2d45ac1e sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6523): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6523): MmsConfig.loadMmsSettings
I/Babel_SMS( 6523): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6523): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6523): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6523): MmsConfig.loadFromResources
,E/Babel_SMS( 6523): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6523): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/TCMD    (  466): NL - Read 312 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 192 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 1004 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 80 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 80 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
I/wpa_supplicant( 1439): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  291): Event received = Associated with c0:ff:d4
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
,W/art     ( 6523): Suspending all threads took: 5.372ms
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1439): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  466): NL - Read 1004 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  291): Event received = WPA: Key negotiation com
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  291): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  291):  STA Connected !!
,E/MDMCTBK (  291): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  291): get_freq !!, resp=2412
I/MDMCTBK (  291): get_freq !!, Strip data
I/MDMCTBK (  291): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  291): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
,D/Tethering(  880):  5
D/Tethering(  880):  7
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  291): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  291): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1201110336
I/MDMCTBK (  291): return from set_get_from_wpa_supplicant
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  291): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  291): , reply_len: 3, ret: 0
E/MDMCTBK (  291): MdmCutbackHndler, resp=OK
E/MDMCTBK (  291): 
D/MDMCTBK (  291): wifi_set_tx_pwr: Exit
D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
W/Settings( 6523): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/Babel_Crash( 6523): startup - clean
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 2
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  880): do suspend false
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b0a87c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1b0a87c0 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel   ( 6523): deleted: false for 0
,W/VideoCapabilities( 6523): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6523): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6523): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6523): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6523): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6523): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6523): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6523): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 5930:android.process.acore/u0a7 (adj 15): empty #7
,E/DHCPCD  ( 6563): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6563): version 5.5.6 starting
,E/DHCPCD  ( 6563): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6563): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6563): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/art     ( 6523): Suspending all threads took: 7.133ms
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_5930/cgroup.procs: No such file or directory
,I/vclib   ( 6523): onServiceConnected
,W/Babel   ( 6523): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6563): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6563): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6563): wlan0: sending REQUEST (xid 0xe8f921bd), next in 3.94 seconds
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1833): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/DHCPCD  ( 6563): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6563): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6563): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 6563): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6563): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6563): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  466): NL - Read 60 bytes from update socket.
D/TCMD    (  466): NL - ignore NL message, type = 20
D/TCMD    (  466): Listening for incoming client connection request
,D/DHCPCD  ( 6563): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880):    accepting network in place of null
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 23:53:11 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450655591810], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450655591787]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/ModemStatsDSDetect( 1534): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1534): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:33000 mC
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2546): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6638 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1477): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 44.253ms
D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2546): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2546): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2546): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2546): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2546): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2546): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2546): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2546): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2546): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2546): [debug] > CusSM.onRadioDown
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 23.623ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 25.368ms
,I/MusicStore( 6638): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6638): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6638): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6638): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager( 6638): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6638): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6638): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6638): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6638): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29b89d46: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6638): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6638): GMSCore installation verified
,I/ConfigStore( 6638): Config Database version: 1
,I/MediaRouter( 6638): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6638): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6638): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6638): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6693 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6638): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6638): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 6327:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6327/cgroup.procs: No such file or directory
,V/Mms     ( 6693): mnc/mcc: 
V/Mms     ( 6693): tag: int value: recipientLimit - 20
,V/Mms     ( 6693): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6693): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6693): tag: int value: maxSubjectLength - 80
V/Mms     ( 6693): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6693): tag: bool value: enableGroupMms - false
,V/Mms     ( 6693):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6693): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6719 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6523:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6523/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6719): Register our PhoneStateListener
,I/art     (  880): Explicit concurrent mark sweep GC freed 53614(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 20MB/30MB, paused 1.428ms total 136.182ms
,D/MobileConnectivityChangeReceiver( 6719): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6719): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 6493:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6493/cgroup.procs: No such file or directory
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1450655518957 min interval config: 0 actual interval: 74771
,I/CheckinService( 1950): Checking schedule, now: 1450655593735 next: 1450655548934
I/CheckinService( 1950): active receiver: enabled
,I/CheckinService( 1950): Preparing to send checkin request
,I/EventLogService( 1950): Accumulating logs since 1450655516010
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6741 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1950): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1950): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6763 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6425): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6425): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6425): BLE supported!!
I/jxcore-log( 6425): 
,W/ResourcesManager( 6763): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6763): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6763): VM with version 2.1.0 has multidex support
I/MultiDex( 6763): install
I/MultiDex( 6763): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6782 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/JNIHelp ( 6763): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6782): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityThread( 6763): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6763): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@128db72f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6763): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6763): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6763): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6763): Install completed successfully. count=14 extracted=0
,I/Babel_SMS( 6782): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6782): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6782): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6782): MmsConfig.loadFromDatabase
,D/WVCdm   (  293): Instantiating CDM.
,I/WVCdm   (  293): CdmEngine::OpenSession
I/WVCdm   (  293): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  293): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,E/Babel_SMS( 6782): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6782): MmsConfig.loadFromResources
E/Babel_SMS( 6782): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6782): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/DrmWidevineDash(  293): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  293): Service_Initialize: starts!
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
E/QSEECOMAPI: (  293): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  293): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
E/QSEECOMAPI: (  293): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  293): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
,D/QSEECOMAPI: (  293): Loaded image: APP id = 3
,D/DrmWidevineDash(  293): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500e000
E/DrmWidevineDash(  293): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500e000
,D/DrmWidevineDash(  293): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  293): hlos api version =  9
D/DrmWidevineDash(  293): tz api version =  8
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  293): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  293): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  293): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  293): OEMCrypto_OpenSession: starts! SID=0xb55e9960
D/DrmWidevineDash(  293): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  293): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_GetRandom: starts! randomData=0xb7d2d688, dataLength=8
D/DrmWidevineDash(  293): OEMCrypto_GetRandom: ends! returns 0
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524295
,D/DrmWidevineDash(  293): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7dc6cd0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  293): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  293): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  293): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  293): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  293): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  293): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e1fd18, idLength=0xb12ff730
,D/DrmWidevineDash(  293): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  293): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  293): hlos api version =  9
D/DrmWidevineDash(  293): tz api version =  8
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  293): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  293): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  293): PrepareKeyRequest: nonce=3563085293
D/DrmWidevineDash(  293): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d26140
D/DrmWidevineDash(  293): message_length=1591, signature=0xb7d02768, signature_length=2972710676
,W/Settings( 6782): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6782): startup - clean
,I/Babel   ( 6782): deleted: false for 0
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6817 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/DrmWidevineDash(  293): OEMCrypto_GenerateRSASignature returns 0
,D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2546): now: 189309 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2546): now: 189311 ,futureTime: 9223372036854775807
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2546): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2546): now: 189311 ,futureTime: 9223372036854775807
D/OtaApp  ( 2546): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WVCdm   (  293): CdmEngine::CloseSession
D/DrmWidevineDash(  293): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  293): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  293): L3 Terminate.
D/DrmWidevineDash(  293): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  293): Service_Uninitialize: starts!
D/QSEECOMAPI: (  293): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  293): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  293): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  293): OEMCrypto_Terminate: ends! returns 0
,D/Central_PollingManager( 1477): now: 189318 ,futureTime: 86473118
D/Central_PollingManager( 1477): Polling alarm set to expire at: 86473118 Current Time: 189318
,D/OtaApp  ( 2546): [debug] > PollingManagerService, now: 189321 ,futureTime: 40842403
D/OtaApp  ( 2546): [debug] > Polling alarm set to expire at: 40842403 Current Time: 189322
,I/NetworkMonitor( 6638): type=WIFI subType= reason=null isConnected=true
,W/VideoCapabilities( 6782): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6782): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6782): Unsupported mime video/mpeg2
,I/art     ( 2546): Explicit concurrent mark sweep GC freed 38526(2MB) AllocSpace objects, 5(126KB) LOS objects, 40% free, 11MB/18MB, paused 1.012ms total 82.125ms
,D/MMApiProvisionService( 2546): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2546): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2546): createDeviceIdOrLogin update_device
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/VideoCapabilities( 6782): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6782): Unrecognized profile 2130706433 for video/avc
,D/MMApiProvisionService( 2546): Not proxy app, so login/provision not allowed
,W/VideoCapabilities( 6782): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6782): Unrecognized profile 2130706433 for video/avc
,D/MMApiProvisionService( 2546): isDeviceProvisioned: deviceId = 2072049230914535424
,W/VideoCapabilities( 6782): Unrecognized profile 2130706433 for video/avc
,D/CCE     ( 2546): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2546): createDeviceIdOrLogin update_device
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2546): isDeviceProvisioned: deviceId = 2072049230914535424
,I/vclib   ( 6782): onServiceConnected
W/Babel   ( 6782): Attempted to change video mute state without an active call.
D/MMApiProvisionService( 2546): set mOutstandingReq to true.
I/ Nonce  ( 2546):  Nonce getNonce 
I/ Nonce  ( 2546):  Nonce Request 
I/ Nonce  ( 2546):  Nonce execute Request 
,D/MMApiWebService( 2546): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2546): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2546): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2546): createDeviceIdOrLogin update_device
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2546): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2546): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2546): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2546): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2546): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2546): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2546): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2546): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2546): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2546): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/Babel   ( 6782): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  880): Killing 6298:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/MMApiWebService( 2546): generating token using payload instead of using session token
,D/ Nonce  ( 2546):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2546): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6298/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6817): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6817): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6817): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6817): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6817): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6817):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6817):   adb logcat -s GAv4
,W/GAv4    ( 6817): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6817): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6850): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/GAv4    ( 6817): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6850): dex2oat took 120.640ms (threads: 4)
,I/Adreno-EGL( 6763): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6763): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6763): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6763): Local Branch: 
I/Adreno-EGL( 6763): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6763): Local Patches: NONE
I/Adreno-EGL( 6763): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6763): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6763): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6763): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6763): Local Branch: 
I/Adreno-EGL( 6763): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6763): Local Patches: NONE
I/Adreno-EGL( 6763): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6763): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6763): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6763): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6763): Local Branch: 
I/Adreno-EGL( 6763): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6763): Local Patches: NONE
I/Adreno-EGL( 6763): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 6817): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6817): Time to load native libraries: 2 ms (timestamps 250-252)
I/LibraryLoader( 6817): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6817): Binding Chromium to main looper Looper (main, tid 1) {460ca1f}
I/LibraryLoader( 6817): Expected native library version number "",actual native library version number ""
I/chromium( 6817): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6817): Initializing chromium process, singleProcess=true
W/art     ( 6817): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6817): ApplicationContext is null in ApplicationStatus
I/Adreno-EGL( 6763): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6763): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6763): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6763): Local Branch: 
I/Adreno-EGL( 6763): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6763): Local Patches: NONE
I/Adreno-EGL( 6763): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
W/chromium( 6817): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6817): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6817): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6817): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6817): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6817): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6817): Local Branch: 
I/Adreno-EGL( 6817): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6817): Local Patches: NONE
I/Adreno-EGL( 6817): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6817): Requires BLUETOOTH permission
,I/NSApplication( 6817): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6893 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6638:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/WVCdm   (  293): CdmEngine::OpenSession
I/WVCdm   (  293): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  293): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  293): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  293): Service_Initialize: starts!
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
,E/QSEECOMAPI: (  293): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  293): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  293): App is not loaded in QSEE
E/QSEECOMAPI: (  293): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  293): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6638/cgroup.procs: No such file or directory
,D/QSEECOMAPI: (  293): Loaded image: APP id = 3
,D/DrmWidevineDash(  293): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  293): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500e000
E/DrmWidevineDash(  293): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500e000
,I/ Nonce  ( 2546):  Nonce Reponse 
D/        ( 2546): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"0b7aa694-9641-4c20-b8ea-86bd56521c56"}
D/MMApiWSBase( 2546): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2546):  Nonce Handle Reponse 
D/MMApiProvisionService( 2546): mOutstandingReq set to false
,D/DrmWidevineDash(  293): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  293): hlos api version =  9
,D/DrmWidevineDash(  293): tz api version =  8
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  293): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  293): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  293): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  293): OEMCrypto_OpenSession: starts! SID=0xb12ff960
D/DrmWidevineDash(  293): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  293): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_GetRandom: starts! randomData=0xb7d2d588, dataLength=8
D/DrmWidevineDash(  293): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  293): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7dc6cd0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  293): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  293): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  293): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  293): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  293): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  293): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e1fd58, idLength=0xb55e9730
,D/DrmWidevineDash(  293): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  293): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  293): hlos api version =  9
D/DrmWidevineDash(  293): tz api version =  8
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  293): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  293): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  293): PrepareKeyRequest: nonce=320118614
D/DrmWidevineDash(  293): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d26140
D/DrmWidevineDash(  293): message_length=1626, signature=0xb7d02788, signature_length=3042875156
,I/art     (  880): Explicit concurrent mark sweep GC freed 14535(695KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.405ms total 119.151ms
,D/MMApiProvisionService( 2546):  pTime 1450652997779 sExp 172742 cTime 1450655596223 tTime 1450825739779
D/MMApiProvisionService( 2546):  No login Required 
,D/DrmWidevineDash(  293): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  293): CdmEngine::CloseSession
D/DrmWidevineDash(  293): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  293): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  293): L3 Terminate.
D/DrmWidevineDash(  293): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  293): Service_Uninitialize: starts!
D/QSEECOMAPI: (  293): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  293): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  293): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  293): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 1950): Classify the device as Phone.
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6917 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6693:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6693/cgroup.procs: No such file or directory
,W/ResourcesManager( 6917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinTask( 1950): Sending checkin request (9450 bytes)
,W/DataUsage( 2546): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6942 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6961 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6741:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  880): Killing 6719:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 6942): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6741/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6719/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1950): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1950): Failed to find provider info for com.google.android.wearable.settings
,I/MusicStore( 6961): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6961): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 1950): Classify the device as Phone.
,I/CheckinTask( 1950): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1950): Checking schedule, now: 1450655597024 next: 1451256734015
I/CheckinService( 1950): active receiver: disabled
,D/CheckinService( 1950): Recording last checkin time for package unspecified as 1450655597033
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6961): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6961): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/ActivityManager(  880): Killing 6782:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6782/cgroup.procs: No such file or directory
,W/ResourcesManager( 6961): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6961): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6961): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6961): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6961): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29b89d46: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6961): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6961): GMSCore installation verified
,I/ConfigStore( 6961): Config Database version: 1
,I/MediaRouter( 6961): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6961): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6961): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Killing 6817:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_6817/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6961): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7004 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 25.427ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.413ms
,I/GHttpClientFactory( 6961): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6961): Using platform SSLCertificateSocketFactory
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 531us total 21.659ms
,I/ActivityManager(  880): Killing 6893:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7004): mnc/mcc: 
V/Mms     ( 7004): tag: int value: recipientLimit - 20
,V/Mms     ( 7004): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7004): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7004): tag: int value: maxSubjectLength - 80
V/Mms     ( 7004): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7004): tag: bool value: enableGroupMms - false
V/Mms     ( 7004):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_6893/cgroup.procs: No such file or directory
,W/ResourcesManager( 7004): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7043 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6917:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6917/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7043): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7043): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7043): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 6942:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6942/cgroup.procs: No such file or directory
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1450655597033 min interval config: 0 actual interval: 890
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
,I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7065 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1950): Checking schedule, now: 1450655597991 next: 1450655627015
I/CheckinService( 1950): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7085 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6961:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6961/cgroup.procs: No such file or directory
,W/ResourcesManager( 7085): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7085): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7085): MmsConfig.loadMmsSettings
I/Babel_SMS( 7085): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7085): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7085): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7085): MmsConfig.loadFromResources
E/Babel_SMS( 7085): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7085): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  880): Explicit concurrent mark sweep GC freed 8969(458KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.494ms total 131.613ms
,W/Settings( 7085): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7085): startup - clean
,I/Babel   ( 7085): deleted: false for 0
,E/global frequency( 2546): no tags to log
,D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7117 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/VideoCapabilities( 7085): Unrecognized profile 2130706433 for video/avc
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
W/AudioCapabilities( 7085): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7085): Unsupported mime video/mpeg2
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/VideoCapabilities( 7085): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7085): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7085): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7085): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7085): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7117): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7117): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/vclib   ( 7085): onServiceConnected
W/Babel   ( 7085): Attempted to change video mute state without an active call.
I/GAv4    ( 7117): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7117):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7117):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7117): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 5635(233KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 662us total 36.110ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7117): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7117): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,W/GAv4    ( 7117): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7085): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7004:com.android.mms/u0a23 (adj 13): empty #7
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/GAv4    ( 7117): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7004/cgroup.procs: No such file or directory
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2546): Explicit concurrent mark sweep GC freed 15994(900KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 989us total 66.890ms
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2546): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2546): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2546): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2546): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2546): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/WebViewFactory( 7117): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7117): Time to load native libraries: 1 ms (timestamps 3928-3929)
I/LibraryLoader( 7117): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7117): Binding Chromium to main looper Looper (main, tid 1) {460ca1f}
I/LibraryLoader( 7117): Expected native library version number "",actual native library version number ""
,I/chromium( 7117): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7117): Initializing chromium process, singleProcess=true
,W/art     ( 7117): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7117): ApplicationContext is null in ApplicationStatus
,W/chromium( 7117): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7117): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7117): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7117): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7117): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7117): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7117): Local Branch: 
I/Adreno-EGL( 7117): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7117): Local Patches: NONE
I/Adreno-EGL( 7117): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7117): Requires BLUETOOTH permission
,I/NSApplication( 7117): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7183 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7043:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7043/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 7521(338KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.933ms total 118.870ms
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7208 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7065:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7065/cgroup.procs: No such file or directory
,W/ResourcesManager( 7208): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7228 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7117:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7228): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7085:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7117/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7085/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2546): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2546): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2546): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2546): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2546): onServiceConnected()
,D/GetNotificationsWS( 2546): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2546): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7257 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2546): started with background data enabled, making sure notification mechanism is enabled
,V/AlarmManager(  880): send {9da858e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {15b567df, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {9da858e, *alarm*:android.intent.action.TIME_TICK} [45ms]
,D/WearableService( 1833): callingUid 10016, callindPid: 1833
,D/LocationInitializer( 1950): Restart initialization of location
,D/AuthorizationBluetoothService( 1833): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1833): [160] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7284 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1833): No location to return for getLastLocation()
W/FusedLocationProvider( 1833): location=null
,I/MusicStore( 7284): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7284): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7284): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7284): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7284): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7284): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7284): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7284): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7284): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29b89d46: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7284): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7284): GMSCore installation verified
,I/ConfigStore( 7284): Config Database version: 1
,I/MediaRouter( 7284): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7284): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7284): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7284): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7315 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7284): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7284): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 7183:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7183/cgroup.procs: No such file or directory
,V/Mms     ( 7315): mnc/mcc: 
,V/Mms     ( 7315): tag: int value: recipientLimit - 20
,V/Mms     ( 7315): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7315): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7315): tag: int value: maxSubjectLength - 80
V/Mms     ( 7315): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7315): tag: bool value: enableGroupMms - false
V/Mms     ( 7315):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7315): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7341 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.776ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 19.397ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.810ms
,I/ActivityManager(  880): Killing 7208:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7341): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7208/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7341): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7341): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  880): Killing 7228:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7228/cgroup.procs: No such file or directory
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1450655597033 min interval config: 0 actual interval: 4680
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1450655597033 min interval config: 0 actual interval: 4681
,I/CheckinService( 1950): Checking schedule, now: 1450655601726 next: 1450655627015
I/CheckinService( 1950): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7361 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1950): Checking schedule, now: 1450655601776 next: 1450655627015
I/CheckinService( 1950): active receiver: disabled
,W/ResourcesManager( 7361): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7361): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7361): MmsConfig.loadMmsSettings
I/Babel_SMS( 7361): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7361): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7361): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7361): MmsConfig.loadFromResources
,E/Babel_SMS( 7361): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7361): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7361): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7361): startup - clean
,I/Babel   ( 7361): deleted: false for 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:34000 mC
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7388 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7361): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7361): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7361): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7361): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7361): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7361): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7361): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7361): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7361): onServiceConnected
,W/Babel   ( 7361): Attempted to change video mute state without an active call.
,I/GAv4    ( 7388): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7388):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7388):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7388): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7388): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7388): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7388): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7388): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7361): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 6763:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,E/lowmemorykiller(  275): Error writing /proc/6763/oom_score_adj; errno=22
,W/GAv4    ( 7388): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7388): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_6763/cgroup.procs: No such file or directory
,I/WebViewFactory( 7388): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7388): Time to load native libraries: 2 ms (timestamps 7253-7255)
,I/LibraryLoader( 7388): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7388): Binding Chromium to main looper Looper (main, tid 1) {460ca1f}
,I/LibraryLoader( 7388): Expected native library version number "",actual native library version number ""
,I/chromium( 7388): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7388): Initializing chromium process, singleProcess=true
,W/art     ( 7388): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7388): ApplicationContext is null in ApplicationStatus
,W/chromium( 7388): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7388): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7388): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7388): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7388): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7388): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7388): Local Branch: 
I/Adreno-EGL( 7388): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7388): Local Patches: NONE
I/Adreno-EGL( 7388): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7388): Requires BLUETOOTH permission
,I/art     (  880): Explicit concurrent mark sweep GC freed 11295(544KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.846ms total 115.422ms
,I/NSApplication( 7388): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7463 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7284:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7284/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7482 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7315:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7315/cgroup.procs: No such file or directory
,W/ResourcesManager( 7482): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7502 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7341:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/EmailService.MarketingOptInSetter( 2546): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager(  880): Killing 7257:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7341/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7257/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2546): bindWebServices(): registering our AIDL callback...
I/SundryService( 2546): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2546): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2546): onServiceConnected()
D/GetNotificationsWS( 2546): onServiceConnected(): Registered for remote service callbacks...
,I/PushService( 2546): started with background data enabled, making sure notification mechanism is enabled
,D/GetNotificationsWS( 2546): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2546): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2546): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2546): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2546): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2546): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7527 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2546): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2546): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2546): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2546): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2546): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2546): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,I/ContactLocale( 7502): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Keyboard.Facilitator( 1418): onFinishInput()
W/IInputConnectionWrapper( 6425): showStatusIcon on inactive InputConnection
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,D/PhoneMonitor( 7527): Register our PhoneStateListener
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,213
,V/SetupWizard( 7527): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 7361:com.google.android.talk/u0a70 (adj 15): empty #7
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7361/cgroup.procs: No such file or directory
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3882fa1b
,I/GCoreNlp( 1833): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1569): Deferring update until onResume
,D/GCM     ( 1833): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7560 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1833): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/AlarmManager(  880): done {15b567df, *walarm*:com.google.android.intent.action.SEND_IDLE} [3676ms]
,D/GCM     ( 1833): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7589 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7388:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7388/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7611 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7628 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7463:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7482:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7463/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7482/cgroup.procs: No such file or directory
,W/ResourcesManager( 7628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7628): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7628): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7628): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7628): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7628): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7628): MmsConfig.loadFromResources
E/Babel_SMS( 7628): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7628): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7628): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7628): startup - clean
,I/Babel   ( 7628): deleted: false for 0
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7661 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.697ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 19.618ms
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 24.835ms
,W/asset   ( 7661): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7661): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7661): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7661): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
W/AudioCapabilities( 7628): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7628): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7628): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
D/PackageBroadcastService( 1950): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
I/PackageBroadcastService( 1950): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@9f83144 new=com.google.android.velvet.VelvetApplication@9f83144
,I/UpdateIcingCorporaServi( 7589): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7693 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1950): updateResources: need to parse f{com.google.android.gms}
,I/vclib   ( 7628): onServiceConnected
W/Babel   ( 7628): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7693): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7628): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7628): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7589): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
,I/ActivityManager(  880): Killing 7560:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7628): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 1950): Explicit concurrent mark sweep GC freed 49443(2MB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 14MB/24MB, paused 1.318ms total 135.726ms
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7560/cgroup.procs: No such file or directory
,W/System  ( 7628): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7628): Installed default security provider GmsCore_OpenSSL
,I/art     (  880): Explicit concurrent mark sweep GC freed 17293(879KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.522ms total 125.753ms
,I/art     ( 1833): Explicit concurrent mark sweep GC freed 85439(4MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 14MB/24MB, paused 1.183ms total 113.473ms
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7723 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7527:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7527/cgroup.procs: No such file or directory
,D/Finsky  ( 7723): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7723): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7723): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7723): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     ( 3143): Explicit concurrent mark sweep GC freed 3016(119KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 464us total 28.422ms
,D/Finsky  ( 7723): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7723): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7723): Skipping gmscore version check
,D/Finsky  ( 7723): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7723): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 7611:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_7611/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 1950): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1950): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 7661:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_7661/cgroup.procs: No such file or directory
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311742, SEQNUM=4465, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-405, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  880): Killing 7589:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7589/cgroup.procs: No such file or directory
,E/BackupManagerService(  880): Timeout restoring application @pm@
W/BackupManagerService(  880): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1833): Restore processing aborted, no more packages
,E/BackupManagerService(  880): Failure getting next package name
E/BackupManagerService(  880): Duplicate finish
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  880): send {a0102ea, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {a0102ea, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311795, SEQNUM=4473, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-430, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311393, SEQNUM=4475, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-482, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1418): run()
I/Keyboard.Facilitator( 1418): flushDynamicLanguageModels()
,I/ConfigService( 1833): onCreate
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ConfigService( 1833): onDestroy
,I/ClearcutLoggerApiImpl( 1833): disconnect managed GoogleApiClient
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {9da858e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {1e6463b6, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  880): send {1a4a56f2, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  880): done {1e6463b6, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [19ms]
,V/AlarmManager(  880): done {1a4a56f2, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [29ms]
,V/AlarmManager(  880): done {9da858e, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1450655597033 min interval config: 0 actual interval: 76555
,I/CheckinService( 1950): Checking schedule, now: 1450655673598 next: 1450655627015
I/CheckinService( 1950): active receiver: enabled
,I/CheckinService( 1950): Preparing to send checkin request
I/EventLogService( 1950): Accumulating logs since 1450655593818
,I/CheckinRequestBuilder( 1950): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1950): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7810 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7810): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7810): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7810): VM with version 2.1.0 has multidex support
,I/MultiDex( 7810): install
I/MultiDex( 7810): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7810): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7810): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7810): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@128db72f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7810): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1833): callingUid 10016, callindPid: 1833
,D/LocationInitializer( 1950): Restart initialization of location
,E/MDM     ( 1833): [218] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1833): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1833): No location to return for getLastLocation()
W/FusedLocationProvider( 1833): location=null
,I/art     ( 7810): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7810): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7810): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  293): Instantiating CDM.
,I/WVCdm   (  293): CdmEngine::OpenSession
I/WVCdm   (  293): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  293): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  293): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  293): Service_Initialize: starts!
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
,E/QSEECOMAPI: (  293): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  293): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
E/QSEECOMAPI: (  293): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  293): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
,D/QSEECOMAPI: (  293): Loaded image: APP id = 3
,D/DrmWidevineDash(  293): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500e000
,E/DrmWidevineDash(  293): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500e000
,D/DrmWidevineDash(  293): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  293): hlos api version =  9
D/DrmWidevineDash(  293): tz api version =  8
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  293): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  293): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  293): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  293): OEMCrypto_OpenSession: starts! SID=0xb54e9960
D/DrmWidevineDash(  293): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  293): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_GetRandom: starts! randomData=0xb7deb858, dataLength=8
D/DrmWidevineDash(  293): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7dc6cd0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  293): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  293): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  293): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  293): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  293): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  293): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e1fd38, idLength=0xbee482b0
,D/DrmWidevineDash(  293): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  293): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  293): hlos api version =  9
D/DrmWidevineDash(  293): tz api version =  8
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  293): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  293): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  293): PrepareKeyRequest: nonce=3869223729
D/DrmWidevineDash(  293): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d26140
D/DrmWidevineDash(  293): message_length=1591, signature=0xb7d02768, signature_length=3202646676
,D/DrmWidevineDash(  293): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  293): CdmEngine::CloseSession
,D/DrmWidevineDash(  293): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  293): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  293): L3 Terminate.
D/DrmWidevineDash(  293): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  293): Service_Uninitialize: starts!
D/QSEECOMAPI: (  293): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  293): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  293): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7854): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7854): dex2oat took 85.002ms (threads: 4)
,I/Adreno-EGL( 7810): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7810): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7810): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7810): Local Branch: 
I/Adreno-EGL( 7810): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7810): Local Patches: NONE
I/Adreno-EGL( 7810): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7810): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7810): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7810): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7810): Local Branch: 
I/Adreno-EGL( 7810): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7810): Local Patches: NONE
I/Adreno-EGL( 7810): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7810): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7810): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7810): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7810): Local Branch: 
I/Adreno-EGL( 7810): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7810): Local Patches: NONE
I/Adreno-EGL( 7810): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7810): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7810): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7810): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7810): Local Branch: 
I/Adreno-EGL( 7810): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7810): Local Patches: NONE
I/Adreno-EGL( 7810): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  293): CdmEngine::OpenSession
I/WVCdm   (  293): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  293): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  293): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  293): Service_Initialize: starts!
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
,E/QSEECOMAPI: (  293): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  293): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
,E/QSEECOMAPI: (  293): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  293): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  293): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  293): App is not loaded in QSEE
,D/QSEECOMAPI: (  293): Loaded image: APP id = 3
,D/DrmWidevineDash(  293): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500e000
E/DrmWidevineDash(  293): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500e000
,D/DrmWidevineDash(  293): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  293): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  293): hlos api version =  9
,D/DrmWidevineDash(  293): tz api version =  8
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  293): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  293): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  293): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  293): OEMCrypto_OpenSession: starts! SID=0xb13ff960
D/DrmWidevineDash(  293): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  293): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_GetRandom: starts! randomData=0xb7dc6f30, dataLength=8
D/DrmWidevineDash(  293): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7d02128, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  293): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  293): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  293): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  293): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  293): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  293): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e1fd58, idLength=0xbee482b0
D/DrmWidevineDash(  293): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  293): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  293): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  293): hlos api version =  9
D/DrmWidevineDash(  293): tz api version =  8
D/DrmWidevineDash(  293): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  293): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  293): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  293): PrepareKeyRequest: nonce=2565854917
D/DrmWidevineDash(  293): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d26140
D/DrmWidevineDash(  293): message_length=1626, signature=0xb7d02788, signature_length=3202646676
,D/DrmWidevineDash(  293): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  293): CdmEngine::CloseSession
D/DrmWidevineDash(  293): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  293): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  293): L3 Terminate.
D/DrmWidevineDash(  293): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  293): Service_Uninitialize: starts!
D/QSEECOMAPI: (  293): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  293): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  293): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  293): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 1950): Classify the device as Phone.
,I/CheckinTask( 1950): Sending checkin request (9454 bytes)
,I/CheckinRequestBuilder( 1950): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1950): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1950): Classify the device as Phone.
,I/CheckinTask( 1950): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1950): Checking schedule, now: 1450655677520 next: 1451256814516
I/CheckinService( 1950): active receiver: disabled
,D/CheckinService( 1950): Recording last checkin time for package unspecified as 1450655677532
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7877 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7877): Register our PhoneStateListener
,V/SetupWizard( 7877): Connected to Gservices successfully
,D/GCM     ( 1833): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Killing 7693:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7502:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7693/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7502/cgroup.procs: No such file or directory
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7899 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2b58df6b
,I/GCoreNlp( 1833): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1569): Deferring update until onResume
,I/art     (  880): Explicit concurrent mark sweep GC freed 23539(1222KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.578ms total 124.674ms
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7939 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7959 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7723:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_7723/cgroup.procs: No such file or directory
,W/ResourcesManager( 7628): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7628): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 7959): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7982 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7877:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7877/cgroup.procs: No such file or directory
,W/asset   ( 7982): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7982): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7982): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7982): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1950): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1950): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@9f83144 new=com.google.android.velvet.VelvetApplication@9f83144
,I/Icing   ( 1950): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 7899): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8008 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8008): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7899): UpdateCorporaTask done [took 131 ms] updated apps [took 131 ms] 
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8037 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7810:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7810/cgroup.procs: No such file or directory
,D/Finsky  ( 8037): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8037): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8037): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8037): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8037): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8037): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8037): Skipping gmscore version check
,D/Finsky  ( 8037): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8037): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 7939:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_7939/cgroup.procs: No such file or directory
,I/Icing   ( 1950): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1950): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 7982:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_7982/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 7628:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7628/cgroup.procs: No such file or directory
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {9da858e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {a0102ea, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {a0102ea, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  880): done {9da858e, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311281, SEQNUM=4495, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14022, POWER_SUPPLY_CHARGE_COUNTER=-730, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 8
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311731, SEQNUM=4499, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16125, POWER_SUPPLY_CHARGE_COUNTER=-1694, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {9da858e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3fe82654, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): send {16a34a22, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  880): send {1c691cb3, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  880): done {3fe82654, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [28ms]
,V/AlarmManager(  880): done {16a34a22, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [44ms]
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8099 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 41.170ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.446ms
,V/AlarmManager(  880): done {9da858e, *alarm*:android.intent.action.TIME_TICK} [150ms]
,I/EventLogService( 1950): Aggregate from 1450655673619 (log), 1450654477160 (data)
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.621ms
,I/GAv4    ( 8099): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8099):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8099):   adb logcat -s GAv4
,W/GAv4    ( 8099): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8099): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8099): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {1c691cb3, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [283ms]
,I/ActivityManager(  880): Killing 7899:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7899/cgroup.procs: No such file or directory
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {9da858e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {5bc59c, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  880): done {9da858e, *alarm*:android.intent.action.TIME_TICK} [56ms]
,V/AlarmManager(  880): done {5bc59c, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [100ms]
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311650, SEQNUM=4508, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-3003, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {9da858e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {ff0dba5, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  880): done {ff0dba5, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [25ms]
,V/AlarmManager(  880): done {9da858e, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311018, SEQNUM=4509, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-3818, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311018, SEQNUM=4510, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311001, SEQNUM=4515, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311602, SEQNUM=4516, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-21, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {9da858e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3fe82654, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): send {1446d957, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  880): send {a316f2b, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  880): Prepared write state in 32ms
,V/AlarmManager(  880): done {3fe82654, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [64ms]
,V/AlarmManager(  880): done {9da858e, *alarm*:android.intent.action.TIME_TICK} [79ms]
,I/ProcessStatsService(  880): Prepared write state in 6ms
,I/ProcessStatsService(  880): Prepared write state in 11ms
,V/AlarmManager(  880): done {1446d957, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [111ms]
,V/AlarmManager(  880): done {a316f2b, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [122ms]
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1833): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-39-22.bin
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311308, SEQNUM=4522, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-15, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310723, SEQNUM=4524, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-25, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311014, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-26, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311602, SEQNUM=4527, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-30, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms),I/ThermalEngine(  302): Sensor:xo_therm_pu2:28000 mC
D/AndroidRuntime( 8188): 
D/AndroidRuntime( 8188): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8188): CheckJNI is OFF
D/AndroidRuntime( 8188): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10397 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 6425:com.test.thalitest/u0a397 (adj 9): stop com.test.thalitest
I/WindowState(  880): WIN DEATH: Window{3ffa2ad4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
W/PackageSettings(  880): Skipping PackageSetting{301c1893 com.example.hello/10377} due to missing metadata
I/ActivityManager(  880):   Force finishing activity ActivityRecord{e2aac99 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{526372a 6425:com.test.thalitest/u0a397}, curProc for 6425: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10397 user=0: pkg removed
I/ActivityManager(  880):   Force finishing activity ActivityRecord{e2aac99 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{e2aac99 u0 com.test.thalitest/.MainActivity t3 f}
I/art     ( 2992): Explicit concurrent mark sweep GC freed 12260(2MB) AllocSpace objects, 35(560KB) LOS objects, 39% free, 7MB/12MB, paused 907us total 42.376ms
I/art     ( 1569): Explicit concurrent mark sweep GC freed 5065(312KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 465us total 61.400ms
W/GeofencerStateMachine( 1833): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1418): resetDictionaries() : en_US
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1418): run()
D/VoicemailCleanupService( 7959): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1418): createOrResetDecoder
I/art     ( 1950): Explicit concurrent mark sweep GC freed 19219(1152KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 14MB/19MB, paused 961us total 158.909ms
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8218 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  880): Explicit concurrent mark sweep GC freed 28296(1962KB) AllocSpace objects, 11(265KB) LOS objects, 33% free, 20MB/30MB, paused 1.575ms total 160.696ms
I/art     (  880): WaitForGcToComplete blocked for 143.830ms for cause Explicit
W/asset   ( 8218): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8218): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8218): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8218): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ConfigService( 1833): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): run()
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = history
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8242 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1418): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1418): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1418): run()
I/StatsUtilsManager( 1418): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1418): shouldRecordStats() = Too Soon
I/ActivityManager(  880): Killing 8008:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  880): Explicit concurrent mark sweep GC freed 6971(387KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 5.593ms total 207.178ms
W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8008/cgroup.procs: No such file or directory
W/ContextImpl( 8242): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/AndroidRuntime( 8188): Shutting down VM
D/PackageBroadcastService( 1950): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1950): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1950): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1950): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1833): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1833): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1950): Module APK com.google.android.play.games already loaded
I/Launcher( 1569): Deferring update until onResume
D/gH_CompatibleDatabase( 1950): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1950): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1950): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1950): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1950): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1950): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1950): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8264 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1950): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1950): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1950): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1950): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1950): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1950): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
V/AlarmManager(  880): send {9da858e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {24af873e, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {31e5a99f, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {871daec, *walarm*:com.motorola.ccc.cce.alarmintent}
I/Icing   ( 1950): doRemovePackageData com.test.thalitest
V/AlarmManager(  880): done {9da858e, *alarm*:android.intent.action.TIME_TICK} [43ms]
W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@9f83144 new=com.google.android.velvet.VelvetApplication@9f83144
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8290 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8319 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 8264): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  880): Killing 3143:com.google.process.gapps/u0a16 (adj 15): empty #7
W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_3143/cgroup.procs: No such file or directory
E/SQLiteLog( 8264): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 8264): Exception thrown from onTableChanged
E/AppDataSearchHelper( 8264): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 8264): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 8264): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 8264): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AppDataSearchHelper( 8264): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 8264): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 8264): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 8264): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 8264): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 8264): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 8264): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 8264): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 8264): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 8264): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 8264): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 8264): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 8264): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 8264): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 8264): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 8264): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 8264): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 8264): 	... 16 more
W/AppDataSearchHelper( 8264): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 8264): UpdateCorporaTask done [took 313 ms] updated apps [took 313 ms] 
I/ActivityManager(  880): Killing 8037:com.android.vending/u0a32 (adj 15): empty #7
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
