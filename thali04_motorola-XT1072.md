#### Test 55613145e2b298d_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 6679): 
D/AndroidRuntime( 6679): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6679): CheckJNI is OFF
D/AndroidRuntime( 6679): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6698 uid=10436 gids={50436, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6679): Shutting down VM
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6698): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6698): Time to load native libraries: 16 ms (timestamps 7482-7498)
,I/LibraryLoader( 6698): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6698): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 6698): Expected native library version number "",actual native library version number ""
,I/chromium( 6698): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6698): Initializing chromium process, singleProcess=true
,W/art     ( 6698): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6698): ApplicationContext is null in ApplicationStatus
,W/chromium( 6698): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{1661a57 u0 com.test.thalitest/.MainActivity t3}
,E/libEGL  ( 6698): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6698): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6698): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6698): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6698): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6698): Local Branch: 
I/Adreno-EGL( 6698): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6698): Local Patches: NONE
I/Adreno-EGL( 6698): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29ff44ba:true
,W/art     ( 6698): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6698): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6698): CordovaWebView is running on device made by: motorola
,W/art     ( 6698): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6698): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6698): Render dirty regions requested: true
,D/Atlas   ( 6698): Validating map...
,W/chromium( 6698): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  882): Explicit concurrent mark sweep GC freed 27928(1358KB) AllocSpace objects, 2(225KB) LOS objects, 33% free, 20MB/30MB, paused 1.531ms total 124.174ms
,I/OpenGLRenderer( 6698): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6698): Enabling debug mode 0
,I/Keyboard.Facilitator( 1422): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1214
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +1s124ms (total +1s215ms)
,W/IInputConnectionWrapper( 6698): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6698): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6698): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6698): Cannot call determinedVisibility() - never saw a connection for the pid: 6698
,D/JsMessageQueue( 6698): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6698): JniHelper::setJavaVM(0xb783c310), pthread_self() = -1212370736
,D/JX-Cordova( 6698): jxcore cordova android initializing
,W/jxcore-log( 6698): Initializing JXcore engine
W/jxcore-log( 6698): JXcore engine is ready
,W/jxcore-log( 6698): Starting JXcore engine
,W/.test.thalitest( 6698): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10436 path="socket:[5586]" dev="sockfs" ino=5586 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6698): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10436 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6698): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10436 path="socket:[6631]" dev="sockfs" ino=6631 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6698): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10436 path="socket:[28775]" dev="sockfs" ino=28775 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6698): Platform android
W/jxcore-log( 6698): 
,W/jxcore-log( 6698): Process ARCH arm
W/jxcore-log( 6698): 
,I/jxcore-log( 6698): JXcore Cordova bridge is ready!
I/jxcore-log( 6698): 
W/jxcore-log( 6698): JXcore engine is started
,I/chromium( 6698): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311083, SEQNUM=4428, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-17427, POWER_SUPPLY_CHARGE_COUNTER=-517, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,I/jxcore-log( 6698): Toggling radios to true
I/jxcore-log( 6698): 
,D/BluetoothAdapter( 6698): enable(): BT is already enabled..!
,D/WifiService(  882): New client listening to asynchronous messages
,D/WifiService(  882): setWifiEnabled: true pid=6698, uid=10436
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6698): Radios toggled
I/jxcore-log( 6698): 
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6698): Received device characteristics:
I/jxcore-log( 6698): Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6698): Bluetooth name: XT1072
I/jxcore-log( 6698): Device name: motorola-XT1072
I/jxcore-log( 6698): 
I/jxcore-log( 6698): Perf Test app loaded loaded
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): check test folder
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): found test : ./testFindPeers.js
I/jxcore-log( 6698): 
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/Tethering(  882): InitialState.processMessage what=4
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882):  0
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6698): found test : ./testSendData.js
I/jxcore-log( 6698): 
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 21
D/TCMD    (  480): Listening for incoming client connection request
,V/NativeCrypto( 1737): Read error: ssl=0xb7c28030: I/O error during system call, Connection timed out
V/NativeCrypto( 1737): SSL shutdown failed: ssl=0xb7c28030: I/O error during system call, Broken pipe
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  882): connected time updated 113756
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6759 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
,D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  882): Start Disconnecting Watchdog 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): ConnectModeState: Network connection lost 
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6759): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/chromium( 6698): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6787 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6513:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_6513/cgroup.procs: No such file or directory
,W/ResourcesManager( 6787): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1737): Scheduling Phenotype for one-off execution 13278 seconds from now (1452523298439)
,D/GetConfigurationSnapshotOperation( 1737): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/Babel_SMS( 6787): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6787): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6787): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6787): MmsConfig.loadFromDatabase
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
E/WifiStateMachine(  882): [1,452,523,298,505 ms] noteScanEnd no scan source
I/wpa_supplicant( 1439): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1439): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,E/Babel_SMS( 6787): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6787): MmsConfig.loadFromResources
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Babel_SMS( 6787): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6787): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/PhenotypeFlagCommitter( 1737): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1737): Using platform SSLCertificateSocketFactory
,W/Settings( 6787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6787): startup - clean
,I/Babel   ( 6787): deleted: false for 0
,D/TCMD    (  480): NL - Read 312 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 192 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1439): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1439): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/MDMCTBK (  294): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  294): get_freq !!, resp=2412
I/MDMCTBK (  294): get_freq !!, Strip data
I/MDMCTBK (  294): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1209713216
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  882): Network connection established
,E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
E/WifiStateMachine(  882): Start Dhcp Watchdog 2
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ec93a73 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ec93a73 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6787): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6787): Unsupported mime audio/amr-wb-plus
,D/Uploader( 1737): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,W/VideoCapabilities( 6787): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6787): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6787): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6787): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6787): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6787): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 6181:android.process.acore/u0a7 (adj 15): empty #7
,E/DHCPCD  ( 6832): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6832): version 5.5.6 starting
E/DHCPCD  ( 6832): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6832): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6832): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_6181/cgroup.procs: No such file or directory
,I/vclib   ( 6787): onServiceConnected
,W/Babel   ( 6787): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6832): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6832): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6832): wlan0: sending REQUEST (xid 0xb8d142e7), next in 3.32 seconds
,D/Uploader( 1737): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1737): Explicit concurrent mark sweep GC freed 91517(4MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 15MB/26MB, paused 1.335ms total 139.917ms
,D/Uploader( 1737): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@396007b1)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14216496)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@20e1b817)
E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3efc9404)
E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5bc6ded)
,D/Uploader( 1737): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1737): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1737): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1737): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1737): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/DHCPCD  ( 6832): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6832): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6832): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6832): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6832): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6832): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 20
D/TCMD    (  480): Listening for incoming client connection request
,D/DHCPCD  ( 6832): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:32000 mC
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  882): Adding iface wlan0 to network 101
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  882): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882):    accepting network in place of null
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 14:41:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452523300738], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452523300719]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524290
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1534): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1534): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6908 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2591): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2591): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2591): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2591): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2591): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2591): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2591): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2591): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2591): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2591): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2591): [debug] > CusSM.onRadioDown
,I/MusicStore( 6908): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6908): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6908): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6908): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6908): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6908): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6908): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6908): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6908): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6908): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6908): GMSCore installation verified
,I/ConfigStore( 6908): Config Database version: 1
,I/MediaRouter( 6908): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6908): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6908): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  882): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/NetworkMonitor( 6908): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6945 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6908): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6908): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 6562:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_6562/cgroup.procs: No such file or directory
,V/Mms     ( 6945): mnc/mcc: 
V/Mms     ( 6945): tag: int value: recipientLimit - 20
,V/Mms     ( 6945): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6945): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6945): tag: int value: maxSubjectLength - 80
V/Mms     ( 6945): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6945): tag: bool value: enableGroupMms - false
V/Mms     ( 6945):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6945): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6976 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6597:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6976): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_6597/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6976): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6976): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 6787:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6787/cgroup.procs: No such file or directory
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1452523228550 min interval config: 0 actual interval: 73590
,I/CheckinService( 1950): Checking schedule, now: 1452523302151 next: 1452523258532
I/CheckinService( 1950): active receiver: enabled
,I/CheckinService( 1950): Preparing to send checkin request
I/EventLogService( 1950): Accumulating logs since 1452523225473
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6995 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 22.486ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.675ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 374us total 22.128ms
,I/CheckinRequestBuilder( 1950): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1950): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  882): Explicit concurrent mark sweep GC freed 50271(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.731ms total 126.775ms
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7013 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7013): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7030 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524295
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,W/ResourcesManager( 7030): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7030): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7030): VM with version 2.1.0 has multidex support
,I/MultiDex( 7030): install
I/MultiDex( 7030): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7030): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel_SMS( 7013): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7013): MmsConfig.loadMmsSettings
I/Babel_SMS( 7013): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7013): MmsConfig.loadFromDatabase
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6698): BLE is supported
I/jxcore-log( 6698): 
,W/ActivityThread( 7030): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7030): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7030): Installed default security provider GmsCore_OpenSSL
,E/Babel_SMS( 7013): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7013): MmsConfig.loadFromResources
,E/Babel_SMS( 7013): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7013): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 7030): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7030): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Settings( 7013): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7013): startup - clean
,I/Babel   ( 7013): deleted: false for 0
,D/NativeLibraryUtils( 7030): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7066 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb548e960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb7aefe90, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7b4ffc0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c23e38, idLength=0xbebd12b0
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=3168874565
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7b2a290
D/DrmWidevineDash(  296): message_length=1591, signature=0xb7b4f728, signature_length=3200062100
,W/VideoCapabilities( 7013): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7013): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7013): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7013): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7013): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7013): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7013): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7013): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7013): onServiceConnected
,W/Babel   ( 7013): Attempted to change video mute state without an active call.
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/Babel   ( 7013): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 6759:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_6759/cgroup.procs: No such file or directory
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2591): now: 189772 ,futureTime: 9223372036854775807
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2591): now: 189775 ,futureTime: 9223372036854775807
D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2591): now: 189775 ,futureTime: 9223372036854775807
D/Tethering(  882): MasterInitialState.processMessage what=3
D/OtaApp  ( 2591): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2591): [debug] > PollingManagerService, now: 189777 ,futureTime: 5649973
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2591): [debug] > Polling alarm set to expire at: 5649973 Current Time: 189778
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1465): now: 189782 ,futureTime: 86474724
D/OtaApp  ( 2591): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/Central_PollingManager( 1465): Polling alarm set to expire at: 86474724 Current Time: 189782
,I/NetworkMonitor( 6908): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2591): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/dex2oat ( 7090): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2591): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2591): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2591): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2591): createDeviceIdOrLogin update_device
,D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2591): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2591): isDeviceProvisioned: deviceId = 2072049230914535424
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7066): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/CCE     ( 2591): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2591): createDeviceIdOrLogin update_device
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7066): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2591): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2591): set mOutstandingReq to true.
I/ Nonce  ( 2591):  Nonce getNonce 
I/ Nonce  ( 2591):  Nonce Request 
I/ Nonce  ( 2591):  Nonce execute Request 
,D/MMApiWebService( 2591): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/GAv4    ( 7066): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7066):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7066):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7066): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7066): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/MMApiProvisionService( 2591): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2591): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2591): createDeviceIdOrLogin update_device
,D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2591): Not proxy app, so login/provision not allowed
,W/GAv4    ( 7066): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 7090): dex2oat took 140.351ms (threads: 4)
,D/MMApiWebService( 2591): generating token using payload instead of using session token
,I/Adreno-EGL( 7030): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7030): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7030): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7030): Local Branch: 
I/Adreno-EGL( 7030): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7030): Local Patches: NONE
I/Adreno-EGL( 7030): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/ Nonce  ( 2591):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,W/GAv4    ( 7066): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/MMApiWSBase( 2591): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,W/GAv4    ( 7066): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 7030): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7030): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7030): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7030): Local Branch: 
I/Adreno-EGL( 7030): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7030): Local Patches: NONE
I/Adreno-EGL( 7030): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 7066): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7066): Time to load native libraries: 5 ms (timestamps 235-240)
I/LibraryLoader( 7066): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7066): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 7066): Expected native library version number "",actual native library version number ""
,I/chromium( 7066): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7066): Initializing chromium process, singleProcess=true
W/art     ( 7066): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7066): ApplicationContext is null in ApplicationStatus
,W/chromium( 7066): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7066): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7066): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7066): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7066): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7066): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7066): Local Branch: 
I/Adreno-EGL( 7066): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7066): Local Patches: NONE
I/Adreno-EGL( 7066): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7066): Requires BLUETOOTH permission
,I/NSApplication( 7066): Starting up...
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7142 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6908:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
,D/DrmWidevineDash(  296): tz api version =  8
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xbebd14e0
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb7af01b8, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7b4ffc0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c23e78, idLength=0xb13a4730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=2293983709
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7b2a290
D/DrmWidevineDash(  296): message_length=1626, signature=0xb7b4f728, signature_length=2973386516
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_6908/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7030): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7030): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7030): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7030): Local Branch: 
I/Adreno-EGL( 7030): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7030): Local Patches: NONE
I/Adreno-EGL( 7030): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ Nonce  ( 2591):  Nonce Reponse 
,D/        ( 2591): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"bfcbca07-e26f-4938-9e31-9c6f4e37a1f6"}
,D/MMApiWSBase( 2591): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2591):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2591): mOutstandingReq set to false
,I/Adreno-EGL( 7030): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7030): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7030): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7030): Local Branch: 
I/Adreno-EGL( 7030): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7030): Local Patches: NONE
I/Adreno-EGL( 7030): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7170 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 6945:com.android.mms/u0a23 (adj 15): empty #7
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 56926(3MB) AllocSpace objects, 37(1359KB) LOS objects, 39% free, 7MB/12MB, paused 1.960ms total 55.595ms
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_6945/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1950): Classify the device as Phone.
,I/art     (  882): Explicit concurrent mark sweep GC freed 14551(698KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.696ms total 118.859ms
,D/MMApiProvisionService( 2591):  pTime 1452467391223 sExp 172742 cTime 1452523304890 tTime 1452640133223
D/MMApiProvisionService( 2591):  No login Required 
,W/ResourcesManager( 7170): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7203 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinTask( 1950): Sending checkin request (9554 bytes)
,W/DataUsage( 2591): invalid counter update blocked: 'err' by 0
,I/ActivityManager(  882): Killing 6976:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_6976/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7224 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6995:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/art     ( 7170): Suspending all threads took: 6.812ms
,I/ContactLocale( 7203): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_6995/cgroup.procs: No such file or directory
,I/MusicStore( 7224): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7224): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7224): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7224): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7224): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7224): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7224): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinRequestBuilder( 1950): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1950): Failed to find provider info for com.google.android.wearable.settings
,W/ActivityThread( 7224): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7224): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7224): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7224): GMSCore installation verified
,I/ConfigStore( 7224): Config Database version: 1
,I/MediaRouter( 7224): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7224): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7224): type=WIFI subType= reason=null isConnected=true
I/CheckinRequestBuilder( 1950): Classify the device as Phone.
,I/CheckinTask( 1950): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1950): Checking schedule, now: 1452523305803 next: 1453124442796
I/CheckinService( 1950): active receiver: disabled
,D/CheckinService( 1950): Recording last checkin time for package unspecified as 1452523305815
,I/ActivityManager(  882): Killing 7066:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/NetworkMonitor( 7224): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Killing 7013:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7066/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7013/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7258 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7224): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7224): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 7142:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7142/cgroup.procs: No such file or directory
,V/Mms     ( 7258): mnc/mcc: 
,V/Mms     ( 7258): tag: int value: recipientLimit - 20
,V/Mms     ( 7258): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7258): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7258): tag: int value: maxSubjectLength - 80
V/Mms     ( 7258): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7258): tag: bool value: enableGroupMms - false
,V/Mms     ( 7258):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7258): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7284 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7170:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7170/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7284): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7284): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7284): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 7203:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7203/cgroup.procs: No such file or directory
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1452523305815 min interval config: 0 actual interval: 637
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7306 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1950): Checking schedule, now: 1452523306519 next: 1452523335796
I/CheckinService( 1950): active receiver: disabled
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7323 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7224:com.google.android.music:main/u0a80 (adj 13): empty #7
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 379us total 26.469ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 22.312ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 21.453ms
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7224/cgroup.procs: No such file or directory
,W/ResourcesManager( 7323): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7323): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7323): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7323): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7323): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7323): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7323): MmsConfig.loadFromResources
,E/Babel_SMS( 7323): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7323): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7323): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7323): startup - clean
,I/Babel   ( 7323): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7354 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7323): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7323): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7323): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7323): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7323): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7323): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7323): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7323): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7323): onServiceConnected
W/Babel   ( 7323): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7354): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7354): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7354): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7354):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7354):   adb logcat -s GAv4
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7354): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7354): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7354): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7323): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 7258:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7354): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7354): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7258/cgroup.procs: No such file or directory
,I/WebViewFactory( 7354): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7354): Time to load native libraries: 1 ms (timestamps 3996-3997)
I/LibraryLoader( 7354): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7354): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7354): Expected native library version number "",actual native library version number ""
I/chromium( 7354): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7354): Initializing chromium process, singleProcess=true
,W/art     ( 7354): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7354): ApplicationContext is null in ApplicationStatus
,W/chromium( 7354): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7354): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7354): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7354): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7354): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7354): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7354): Local Branch: 
I/Adreno-EGL( 7354): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7354): Local Patches: NONE
I/Adreno-EGL( 7354): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  882): Explicit concurrent mark sweep GC freed 10776(555KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.690ms total 117.538ms
,W/AudioManagerAndroid( 7354): Requires BLUETOOTH permission
,I/NSApplication( 7354): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7423 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7284:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7284/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7442 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7306:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7306/cgroup.procs: No such file or directory
,W/ResourcesManager( 7442): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7465 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7354:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7465): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7323:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7354/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7323/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2591): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2591): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2591): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2591): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2591): onServiceConnected()
,D/GetNotificationsWS( 2591): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2591): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2591): started with background data enabled, making sure notification mechanism is enabled
,E/global frequency( 2591): no tags to log
,D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7490 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 4400(182KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 633us total 28.451ms
,I/art     ( 2591): Explicit concurrent mark sweep GC freed 18527(1076KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.128ms total 87.108ms
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/WearableService( 1737): callingUid 10016, callindPid: 1737
,D/LocationInitializer( 1950): Restart initialization of location
,D/AuthorizationBluetoothService( 1737): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1737): [197] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     (  882): Explicit concurrent mark sweep GC freed 7457(321KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.575ms total 130.185ms
,V/AlarmManager(  882): send {3a1b1bd0, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7526 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2591): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,W/GCoreFlp( 1737): No location to return for getLastLocation()
W/FusedLocationProvider( 1737): location=null
,D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2591): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2591): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2591): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2591): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MusicStore( 7526): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7526): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7526): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7526): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7526): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7526): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7526): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7526): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7526): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7526): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7526): GMSCore installation verified
,I/ConfigStore( 7526): Config Database version: 1
,I/MediaRouter( 7526): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7526): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7526): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7526): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7562 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7526): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7526): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 7423:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7562): mnc/mcc: 
V/Mms     ( 7562): tag: int value: recipientLimit - 20
,V/Mms     ( 7562): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7562): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7562): tag: int value: maxSubjectLength - 80
V/Mms     ( 7562): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7562): tag: bool value: enableGroupMms - false
,V/Mms     ( 7562):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7423/cgroup.procs: No such file or directory
,W/ResourcesManager( 7562): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7588 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7442:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7588): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7442/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7588): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7588): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 7465:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7465/cgroup.procs: No such file or directory
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1452523305815 min interval config: 0 actual interval: 4439
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1452523305815 min interval config: 0 actual interval: 4441
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7607 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1950): Checking schedule, now: 1452523310313 next: 1452523335796
I/CheckinService( 1950): active receiver: disabled
,I/CheckinService( 1950): Checking schedule, now: 1452523310339 next: 1452523335796
I/CheckinService( 1950): active receiver: disabled
,W/ResourcesManager( 7607): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:33000 mC
,I/Babel_SMS( 7607): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7607): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7607): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7607): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7607): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7607): MmsConfig.loadFromResources
E/Babel_SMS( 7607): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7607): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7607): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7607): startup - clean
,I/Babel   ( 7607): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7640 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7607): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7607): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7607): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7607): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7607): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7607): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7607): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7607): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7607): onServiceConnected
,W/Babel   ( 7607): Attempted to change video mute state without an active call.
,I/GAv4    ( 7640): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7640):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7640):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7640): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/Babel   ( 7607): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 7030:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7640): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7640): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7640): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_7030/cgroup.procs: No such file or directory
,W/GAv4    ( 7640): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7640): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7640): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7640): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7640): Time to load native libraries: 1 ms (timestamps 7551-7552)
I/LibraryLoader( 7640): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7640): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7640): Expected native library version number "",actual native library version number ""
,I/chromium( 7640): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7640): Initializing chromium process, singleProcess=true
,W/art     ( 7640): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7640): ApplicationContext is null in ApplicationStatus
,W/chromium( 7640): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7640): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7640): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7640): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7640): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7640): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7640): Local Branch: 
I/Adreno-EGL( 7640): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7640): Local Patches: NONE
I/Adreno-EGL( 7640): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7640): Requires BLUETOOTH permission
,I/NSApplication( 7640): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7711 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7526:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 23.793ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 330us total 21.284ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 380us total 22.057ms
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7526/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7730 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7562:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7562/cgroup.procs: No such file or directory
,W/ResourcesManager( 7730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7750 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7490:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7750): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7588:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7588/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2591): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7490/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2591): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2591): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2591): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2591): onServiceConnected()
D/GetNotificationsWS( 2591): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2591): unbindWebServices(): un-registering our AIDL callback...
,W/ResourcesManager( 1552): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,D/OtaApp  ( 2591): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2591): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2591): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2591): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2591): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2591): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7786 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2591): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2591): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/OtaApp  ( 2591): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/Launcher( 1571): Deferring update until onResume
,I/art     (  882): Explicit concurrent mark sweep GC freed 18636(937KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.556ms total 124.422ms
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/IInputConnectionWrapper( 6698): showStatusIcon on inactive InputConnection
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@31e943b1
,I/Keyboard.Facilitator( 1422): onFinishInput()
,I/GCoreNlp( 1737): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PhoneMonitor( 7786): Register our PhoneStateListener
,I/LaunchCheckinHandler(  882): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,322
,V/SetupWizard( 7786): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 7607:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7607/cgroup.procs: No such file or directory
,D/GCM     ( 1737): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1737): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7809 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  882): done {3a1b1bd0, *walarm*:com.google.android.intent.action.SEND_IDLE} [3682ms]
,D/GCM     ( 1737): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7838 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7640:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7640/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7860 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7877 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7711:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  882): Killing 7730:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7711/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7730/cgroup.procs: No such file or directory
,W/ResourcesManager( 7877): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7877): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7877): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7877): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7877): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7877): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7877): MmsConfig.loadFromResources
,E/Babel_SMS( 7877): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7877): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7877): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7877): startup - clean
,I/Babel   ( 7877): deleted: false for 0
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7915 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7877): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7877): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7877): Unsupported profile 4 for video/mp4v-es
W/asset   ( 7915): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7915): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7915): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7915): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7877): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 1950): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1950): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7838): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7942 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1950): Explicit concurrent mark sweep GC freed 45875(2MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 15MB/25MB, paused 1.325ms total 99.289ms
,I/Icing   ( 1950): updateResources: need to parse f{com.google.android.gms}
,I/vclib   ( 7877): onServiceConnected
,W/Babel   ( 7877): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7877): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7877): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7942): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7838): UpdateCorporaTask done [took 238 ms] updated apps [took 238 ms] 
,V/JNIHelp ( 7877): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  882): Killing 7809:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/System  ( 7877): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7877): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7809/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7976 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7786:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7786/cgroup.procs: No such file or directory
,D/Finsky  ( 7976): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7976): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7976): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7976): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 3056(120KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 335us total 26.145ms
,D/Finsky  ( 7976): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7976): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7976): Skipping gmscore version check
,D/Finsky  ( 7976): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7976): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 7860:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_7860/cgroup.procs: No such file or directory
,D/TaskPersister(  882): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 1950): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1950): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 7915:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_7915/cgroup.procs: No such file or directory
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311199, SEQNUM=4476, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-606, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,E/BackupManagerService(  882): Timeout restoring application @pm@
W/BackupManagerService(  882): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1737): Restore processing aborted, no more packages
,E/BackupManagerService(  882): Failure getting next package name
,E/BackupManagerService(  882): Duplicate finish
,I/ActivityManager(  882): Killing 7838:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_7838/cgroup.procs: No such file or directory
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310353, SEQNUM=4486, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-653, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310535, SEQNUM=4490, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-697, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1422): run()
,I/Keyboard.Facilitator( 1422): flushDynamicLanguageModels()
,I/ConfigService( 1737): onCreate
,I/ConfigService( 1737): onDestroy
,I/ClearcutLoggerApiImpl( 1737): disconnect managed GoogleApiClient
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  882): send {2cec5545, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {2e2defb, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  882): send {1b4fd8b6, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  882): done {2e2defb, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [16ms]
,V/AlarmManager(  882): done {1b4fd8b6, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [30ms]
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1452523305815 min interval config: 0 actual interval: 76396
,V/AlarmManager(  882): done {2cec5545, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/CheckinService( 1950): Checking schedule, now: 1452523382234 next: 1452523335796
I/CheckinService( 1950): active receiver: enabled
,I/CheckinService( 1950): Preparing to send checkin request
I/EventLogService( 1950): Accumulating logs since 1452523302242
,I/CheckinRequestBuilder( 1950): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1950): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  882): Explicit concurrent mark sweep GC freed 16855(893KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.509ms total 119.253ms
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8091 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 28.155ms
,W/ResourcesManager( 8091): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8091): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.364ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.511ms
,I/MultiDex( 8091): VM with version 2.1.0 has multidex support
,I/MultiDex( 8091): install
I/MultiDex( 8091): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8091): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8091): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8091): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8091): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1737): callingUid 10016, callindPid: 1737
,E/MDM     ( 1737): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1737): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1950): Restart initialization of location
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1737): No location to return for getLastLocation()
,W/FusedLocationProvider( 1737): location=null
,I/art     ( 8091): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8091): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8091): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
I/WVCdm   (  296): CdmEngine::OpenSession
,I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  296): Service_Initialize: starts!
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb558e960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb7af05a0, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7bd8480, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c23e58, idLength=0xbebd12b0
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=1417650074
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7b2a290
D/DrmWidevineDash(  296): message_length=1591, signature=0xb7b54940, signature_length=3200062100
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8131): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8131): dex2oat took 58.835ms (threads: 4)
,I/Adreno-EGL( 8091): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8091): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8091): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8091): Local Branch: 
I/Adreno-EGL( 8091): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8091): Local Patches: NONE
I/Adreno-EGL( 8091): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8091): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8091): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8091): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8091): Local Branch: 
I/Adreno-EGL( 8091): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8091): Local Patches: NONE
I/Adreno-EGL( 8091): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb12a4960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb7c1d4c8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c1d918, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c23e78, idLength=0xbebd12b0
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=3239660197
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7b2a290
,D/DrmWidevineDash(  296): message_length=1626, signature=0xb7b09c98, signature_length=3200062100
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8091): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8091): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8091): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8091): Local Branch: 
I/Adreno-EGL( 8091): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8091): Local Patches: NONE
I/Adreno-EGL( 8091): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8091): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8091): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8091): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8091): Local Branch: 
I/Adreno-EGL( 8091): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8091): Local Patches: NONE
I/Adreno-EGL( 8091): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1950): Classify the device as Phone.
,I/CheckinTask( 1950): Sending checkin request (9552 bytes)
,I/CheckinResponseProcessor( 1950): From server: 1 gservices updates and 0 deletes
,I/CertBlacklister(  882): Certificate blacklist changed, updating...
,I/CertBlacklister(  882): Certificate blacklist updated
,I/GservicesProvider( 4054): main difference update completed
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=8162 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1950): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1950): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  882): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=8195 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,E/UpdateRequestReceiver( 8195): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 8195): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 8195): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 8195): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinService( 1950): Checkin interval check for package: unspecified last checkin: 1452523305815 min interval config: 0 actual interval: 81198
,I/SystemUpdateService( 1950): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1950): onCreate
,D/SystemUpdateService( 1950): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1950): cancelUpdate (empty URL)
I/SystemUpdateService( 1950): active receiver: disabled
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 8423(423KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 851us total 35.217ms
,I/CheckinRequestBuilder( 1950): Classify the device as Phone.
,I/art     ( 1950): Explicit concurrent mark sweep GC freed 10586(639KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 14MB/24MB, paused 1.187ms total 79.082ms
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 2975(111KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 603us total 27.019ms
,I/ActivityManager(  882): Killing 7750:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7750/cgroup.procs: No such file or directory
,D/SystemUpdateService( 1950): onDestroy
,I/CheckinTask( 1950): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/SystemEventReceiver( 1950): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1950): Updating ocr activity enabled=false
,I/CheckinService( 1950): Checking schedule, now: 1452523387516 next: 1453124524484
I/CheckinService( 1950): active receiver: disabled
,I/CheckinService( 1950): Checking schedule, now: 1452523387569 next: 1453124524484
I/CheckinService( 1950): active receiver: disabled
,D/CheckinService( 1950): Recording last checkin time for package unspecified as 1452523387574
,W/ActivityManager(  882): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1950): Updating downloaded model state (gservices changed)
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 2780(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 515us total 24.239ms
,I/art     ( 1737): Explicit concurrent mark sweep GC freed 62752(3MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 13MB/23MB, paused 1.046ms total 87.458ms
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3abab20)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18fbccd9)
,E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2476869e)
E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fafa57f)
E/DataBuffer( 1737): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@170594c)
,D/GCM     ( 1737): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ActivityManager(  882): Killing 7942:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7942/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 7976:com.android.vending/u0a32 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_7976/cgroup.procs: No such file or directory
,I/GCoreUlr( 1737): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=8262 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/GCoreUlr( 1737): DispatchingService.onCreate()
,I/GCoreUlr( 1737): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     (  882): Explicit concurrent mark sweep GC freed 16844(855KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.491ms total 114.442ms
,I/GCoreUlr( 1737): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1737): Unbound from all location providers
I/GCoreUlr( 1737): Place inference reporting - stopped
,I/GCoreUlr( 1737): DispatchingService.onDestroy()
I/GCoreUlr( 1737): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1737): Unbound from all location providers
,I/GCoreUlr( 1737): Place inference reporting - stopped
,I/SearchBackgroundTaskFac( 8262): refreshing internal icing corpora
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=8297 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7877:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7877/cgroup.procs: No such file or directory
,I/GservicesUpdateTask( 8262): Updating Gservices keys
,I/UpdateIcingCorporaServi( 8262): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 8262): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,I/ActivityManager(  882): Killing 8195:com.google.android.configupdater/u0a54 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10054/pid_8195/cgroup.procs: No such file or directory
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 2496(98KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 578us total 28.133ms
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8339 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8339): Register our PhoneStateListener
,V/SetupWizard( 8339): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 8162:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_8162/cgroup.procs: No such file or directory
,D/GCM     ( 1737): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8369 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@441e757
,W/ResourcesManager( 8369): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GCoreNlp( 1737): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1571): Deferring update until onResume
,I/Babel_SMS( 8369): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8369): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8369): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8369): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8369): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8369): MmsConfig.loadFromResources
,E/Babel_SMS( 8369): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8369): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8369): startup - clean
,I/Babel   ( 8369): deleted: false for 0
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8407 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8369): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8369): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8369): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8369): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8369): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8430 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 8297:com.google.android.apps.photos/u0a88 (adj 15): empty #7
W/VideoCapabilities( 8369): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8369): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 8407): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/VideoCapabilities( 8369): Unrecognized profile 2130706433 for video/avc
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_8297/cgroup.procs: No such file or directory
,W/asset   ( 8430): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8430): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8430): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8430): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/art     ( 8369): Suspending all threads took: 6.765ms
,D/PackageBroadcastService( 1950): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1950): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 8262): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/Icing   ( 1950): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 8262): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8459 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 8369): onServiceConnected
W/Babel   ( 8369): Attempted to change video mute state without an active call.
,W/ResourcesManager( 8369): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8369): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 8459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 8369): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8369): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8369): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1737): Explicit concurrent mark sweep GC freed 15822(925KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/23MB, paused 1.094ms total 73.562ms
,I/art     (  882): Explicit concurrent mark sweep GC freed 17837(924KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.373ms total 115.846ms
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8489 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8339:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_8339/cgroup.procs: No such file or directory
,D/Finsky  ( 8489): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8489): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8489): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8489): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8489): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8489): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 8489): Skipping gmscore version check
,D/Finsky  ( 8489): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8489): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 8091:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_8091/cgroup.procs: No such file or directory
,I/Icing   ( 1950): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 1950): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1950): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 8430:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_8430/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 8262:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_8262/cgroup.procs: No such file or directory
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6698): Connected to the server!
I/jxcore-log( 6698): 
,I/chromium( 6698): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310725, SEQNUM=4532, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-882, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 8
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {2cec5545, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {2a7b2ee9, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {2a7b2ee9, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  882): done {2cec5545, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {2cec5545, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {ff4276e, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  882): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8561 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 41.039ms
,V/AlarmManager(  882): done {2cec5545, *alarm*:android.intent.action.TIME_TICK} [109ms]
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.086ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 25.566ms
,I/GAv4    ( 8561): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8561):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8561):   adb logcat -s GAv4
,W/GAv4    ( 8561): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8561): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8561): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  882): Killing 8369:com.google.android.talk/u0a70 (adj 15): empty #7
,V/AlarmManager(  882): done {ff4276e, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [392ms]
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_8369/cgroup.procs: No such file or directory
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6698): --- start :testFindPeers.js---
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): testFindPeers created [object Object]
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): serverPort is 8876
I/jxcore-log( 6698): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): bind: Binding a new listener
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6698): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6698): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): start: OK
I/io.jxcore.node.ConnectionHelper( 6698): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6698): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6698): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6698): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): start: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6698): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service
,D/WifiP2pService(  882): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): start: Starting P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setState: RUNNING
I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper( 6698): start: OK
,I/jxcore-log( 6698): StartBroadcasting started ok
I/jxcore-log( 6698): 
,I/chromium( 6698): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6698): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6698): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6698): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6698): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service request added successfully
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-35
I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service discovery started successfully
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-27
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 6698): 
I/jxcore-log( 6698): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6698): 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 6698): 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 6698): 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 6698): 
I/jxcore-log( 6698): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 6698): 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 0a
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 0a
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 0a
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 0a
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1439): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
,D/WifiP2pService(  882): InactiveState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 1 c0
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
D/WifiP2pManager( 6698): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service request added successfully
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service discovery started successfully
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 6698): 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 6698): 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-54
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 ee
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 ee
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 0a
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 0a
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 92
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 2 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1439): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6698): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service request added successfully
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service discovery started successfully
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 6698): 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 3 
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 4 c0
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 a2
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 a2
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 6698): 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 7e
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 7e
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 A3-1] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerLost: [E0:DB:10:14:E2:C0 Note4-1]
D/io.jxcore.node.ConnectionHelper( 6698): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] removed
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] not available
I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":false}]
I/jxcore-log( 6698): 
I/io.jxcore.node.ConnectionHelper( 6698): onPeerLost: [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 6698): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] removed
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] not available
I/jxcore-log( 6698): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":false}]
I/jxcore-log( 6698): 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 4 
,I/jxcore-log( 6698): timeout now
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): weAreDoneNow
I/jxcore-log( 6698): 
I/jxcore-log( 6698): done, now sending data to server
I/jxcore-log( 6698): 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1439): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 6698): teardown
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): testFindPeers stopped
I/jxcore-log( 6698): 
I/io.jxcore.node.ConnectionHelper( 6698): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6698): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6698): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): stop: Stopping services
D/WifiP2pService(  882): InactiveState{ when=0 what=139298 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139298 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): stop: Stopping P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: NOT_INITIALIZED
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139307 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6698): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setState: NOT_STARTED
,I/jxcore-log( 6698): StopBroadcasting went ok
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): --- start :testSendData.js---
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 13
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): daya100000
I/jxcore-log( 6698): 
I/jxcore-log( 6698): check server
I/jxcore-log( 6698): 
I/jxcore-log( 6698): serverPort is 33114
I/jxcore-log( 6698): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): bind: Binding a new listener
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6698): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6698): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): start: OK
I/io.jxcore.node.ConnectionHelper( 6698): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6698): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6698): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): start: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6698): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState add service
D/WifiP2pService(  882): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): start: Starting P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6698): start: OK
,I/jxcore-log( 6698): StartBroadcasting started ok
I/jxcore-log( 6698): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6698): Waiting for incoming connections...
,I/jxcore-log( 6698): [ { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 6698):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 6698):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 6698):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 6698):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 6698):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 6698):   { address: 'F4:F1:E1:5C:3B:E2', tryCount: 0 },
I/jxcore-log( 6698):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 6698):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 6698):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 6698):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 6698):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 6698):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 } ]
I/jxcore-log( 6698): 
I/jxcore-log( 6698): startWithNextDevice
I/jxcore-log( 6698): 
I/jxcore-log( 6698): do fake peer & start
I/jxcore-log( 6698): 
I/jxcore-log( 6698): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:47:38.626Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:47:38.626Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:47:38.626Z SendDataConnector.js: do connect now
I/jxcore-log( 6698): 
I/io.jxcore.node.ConnectionHelper( 6698): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): connect: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 6698): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 820)
W/BluetoothAdapter( 6698): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 6698): 2016-01-11T14:47:38.701Z SendDataTCPServer.js: TCP/IP server is bound to port: 33114
I/jxcore-log( 6698): 
,I/chromium( 6698): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6698): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6698): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 6698): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 6698): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6698): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6698): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1439): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6698): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery stopped successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/BTIF_SOCK( 2464): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 5 c0
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 5 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 6 c0
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 6 
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 7 c0
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnectionTimeout: [7C:F9:0E:34:8A:A0 S5-1]
I/jxcore-log( 6698): 2016-01-11T14:47:53.700Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] timed out
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:47:53.700Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] timed out
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:47:53.701Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6698): 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/jxcore-log( 6698): 2016-01-11T14:47:58.702Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:47:58.702Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  882): InitialState.processMessage what=4
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
,D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882):  0
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  882): NETWORK_DISCONNECTION_EVENT in connected state BSSID=c0:ff:d4:d3:aa:48 RSSI=-127 freq=-1 was debouncing=false reason=0 ajst=0
E/WifiStateMachine(  882): Missed CTRL-EVENT-DISCONNECTED, disconnect
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  480): NL - Read 60 bytes from update socket.
,D/TCMD    (  480): NL - ignore NL message, type = 21
D/TCMD    (  480): Listening for incoming client connection request
,V/NativeCrypto( 1737): Read error: ssl=0xb7b65390: I/O error during system call, Connection timed out
,V/NativeCrypto( 1737): SSL shutdown failed: ssl=0xb7b65390: I/O error during system call, Broken pipe
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/WifiMetrics(  882): connected time updated 494962
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1950): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=8638 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
,W/ResourcesManager( 8638): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8658 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8407:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_8407/cgroup.procs: No such file or directory
,W/ResourcesManager( 8658): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8658): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8658): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8658): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8658): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8658): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8658): MmsConfig.loadFromResources
,E/Babel_SMS( 8658): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8658): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8658): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8658): startup - clean
,I/Babel   ( 8658): deleted: false for 0
,W/VideoCapabilities( 8658): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8658): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8658): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8658): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8658): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8658): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8658): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8658): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 8459:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 7 
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_8459/cgroup.procs: No such file or directory
,I/vclib   ( 8658): onServiceConnected
W/Babel   ( 8658): Attempted to change video mute state without an active call.
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
,I/jxcore-log( 6698): 2016-01-11T14:48:03.710Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:48:03.713Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:48:03.716Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:48:03.716Z SendDataConnector.js: do connect now
I/jxcore-log( 6698): 
,I/io.jxcore.node.ConnectionHelper( 6698): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 6698): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): connect: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 6698): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 822)
W/BluetoothAdapter( 6698): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2464): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2591): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8699 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/CCE     ( 2591): Registering with Alarm Manager to restart CCE
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1465): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2591): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2591): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2591): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2591): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2591): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2591): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2591): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2591): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2591): [debug] > CusSM.onRadioDown
,I/MusicStore( 8699): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8699): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8699): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8699): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8699): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8699): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8699): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8699): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8699): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8699): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8699): GMSCore installation verified
,I/ConfigStore( 8699): Config Database version: 1
,I/MediaRouter( 8699): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8699): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8747 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8699): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8699): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 8489:com.android.vending/u0a32 (adj 15): empty #7
,V/Mms     ( 8747): mnc/mcc: 
,V/Mms     ( 8747): tag: int value: recipientLimit - 20
V/Mms     ( 8747): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8747): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8747): tag: int value: maxSubjectLength - 80
V/Mms     ( 8747): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8747): tag: bool value: enableGroupMms - false
,V/Mms     ( 8747):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_8489/cgroup.procs: No such file or directory
,W/ResourcesManager( 8747): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8778 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8561:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10055/pid_8561/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8778): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8778): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8778): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 1950): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1950): num queued entries: 0
,I/iu.UploadsManager( 1950): num updated entries: 0
,I/iu.SyncManager( 1950): NEXT; no task
,I/ActivityManager(  882): Killing 8658:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_8658/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8796 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8816 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8638:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_8638/cgroup.procs: No such file or directory
,W/ResourcesManager( 8816): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8816): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 8816): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8816): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8816): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8816): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8816): MmsConfig.loadFromResources
,E/Babel_SMS( 8816): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8816): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  882): Explicit concurrent mark sweep GC freed 36044(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.489ms total 136.502ms
,W/Settings( 8816): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8816): startup - clean
,I/Babel   ( 8816): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8848 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8816): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8816): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8816): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8816): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8816): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8816): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8816): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8816): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8816): onServiceConnected
,W/Babel   ( 8816): Attempted to change video mute state without an active call.
I/Babel   ( 8816): connection state changed from UNKNOWN to DISCONNECTED
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8848): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager(  882): Killing 8699:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/GAv4    ( 8848): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8848):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8848):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8848): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8848): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8848): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_8699/cgroup.procs: No such file or directory
,W/GAv4    ( 8848): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8848): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8848): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8848): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8848): Time to load native libraries: 2 ms (timestamps 3280-3282)
,I/LibraryLoader( 8848): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8848): Binding Chromium to main looper Looper (main, tid 1) {38f40ea1}
,I/LibraryLoader( 8848): Expected native library version number "",actual native library version number ""
I/chromium( 8848): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8848): Initializing chromium process, singleProcess=true
,W/art     ( 8848): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8848): ApplicationContext is null in ApplicationStatus
,W/chromium( 8848): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8848): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8848): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8848): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8848): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8848): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8848): Local Branch: 
I/Adreno-EGL( 8848): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8848): Local Patches: NONE
I/Adreno-EGL( 8848): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 8848): Starting up...
,W/AudioManagerAndroid( 8848): Requires BLUETOOTH permission
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8918 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8747:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_8747/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8937 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8778:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_8778/cgroup.procs: No such file or directory
,W/ResourcesManager( 8937): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8957 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 22.728ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 19.249ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.940ms
,I/ActivityManager(  882): Killing 8816:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 8957): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 8796:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2591): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_8816/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_8796/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2591): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2591): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2591): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2591): onServiceConnected()
D/GetNotificationsWS( 2591): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2591): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8986 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 8986): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8986): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8986): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8986): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8986): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8986): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8986): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8986): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8986): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8986): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8986): GMSCore installation verified
,I/ConfigStore( 8986): Config Database version: 1
,I/MediaRouter( 8986): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8986): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9018 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8986): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8986): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 8848:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,V/Mms     ( 9018): mnc/mcc: 
V/Mms     ( 9018): tag: int value: recipientLimit - 20
V/Mms     ( 9018): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9018): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9018): tag: int value: maxSubjectLength - 80
V/Mms     ( 9018): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9018): tag: bool value: enableGroupMms - false
V/Mms     ( 9018):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_8848/cgroup.procs: No such file or directory
,V/AlarmManager(  882): send {2cec5545, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {9c013cb, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/ResourcesManager( 9018): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9044 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,V/AlarmManager(  882): done {2cec5545, *alarm*:android.intent.action.TIME_TICK} [66ms]
,I/ActivityManager(  882): Killing 8918:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 9044): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_8918/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 9044): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9044): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 8937:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_8937/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9066 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9087 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8957:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_8957/cgroup.procs: No such file or directory
,W/ResourcesManager( 9087): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9087): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9087): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9087): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9087): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9087): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9087): MmsConfig.loadFromResources
E/Babel_SMS( 9087): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9087): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9087): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9087): startup - clean
,I/Babel   ( 9087): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9118 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 9087): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 9087): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 9087): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9087): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9087): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9087): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9087): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9087): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 9087): onServiceConnected
W/Babel   ( 9087): Attempted to change video mute state without an active call.
,I/Babel   ( 9087): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  882): Killing 8986:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  882): Explicit concurrent mark sweep GC freed 13930(734KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 4.890ms total 129.883ms
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_8986/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9118): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9118): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 9118): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9118):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9118):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9118): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9118): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9118): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9118): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9118): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 9118): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9118): Time to load native libraries: 1 ms (timestamps 6256-6257)
,I/LibraryLoader( 9118): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9118): Binding Chromium to main looper Looper (main, tid 1) {38f40ea1}
,I/LibraryLoader( 9118): Expected native library version number "",actual native library version number ""
I/chromium( 9118): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9118): Initializing chromium process, singleProcess=true
,W/art     ( 9118): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9118): ApplicationContext is null in ApplicationStatus
,W/chromium( 9118): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9118): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9118): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9118): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9118): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9118): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9118): Local Branch: 
I/Adreno-EGL( 9118): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9118): Local Patches: NONE
I/Adreno-EGL( 9118): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 9118): Starting up...
,W/AudioManagerAndroid( 9118): Requires BLUETOOTH permission
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9188 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9018:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_9018/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9207 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 9044:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_9044/cgroup.procs: No such file or directory
,W/ResourcesManager( 9207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9227 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9087:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 9227): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_9087/cgroup.procs: No such file or directory
,V/AlarmManager(  882): done {9c013cb, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [2246ms]
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9260 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9118:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_9118/cgroup.procs: No such file or directory
,W/ResourcesManager( 9260): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9260): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9260): MmsConfig.loadMmsSettings
I/Babel_SMS( 9260): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9260): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9260): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 9260): MmsConfig.loadFromResources
E/Babel_SMS( 9260): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9260): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9260): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9260): startup - clean
,I/Babel   ( 9260): deleted: false for 0
,W/VideoCapabilities( 9260): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9260): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9260): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9260): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 9260): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9260): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9260): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9260): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 1950:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  882): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@31ca5ce7)
D/WifiService(  882): Client connection lost with reason: 4
,D/ConnectivityService(  882): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  882): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_1950/cgroup.procs: No such file or directory
,I/vclib   ( 9260): onServiceConnected
,W/Babel   ( 9260): Attempted to change video mute state without an active call.
,W/bt-sdp  ( 2464): SDP - Rcvd conn cnf with error: 0x8  CID 0x40
,E/bt-btif ( 2464): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2464): invalid rfc slot id: 6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 820)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Maximum number of allowed retries (0) reached, giving up... (thread ID: 820)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Exiting thread (thread ID: 820)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): shutdown (thread ID: 820)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:34:8A:A0 S5-1]
,I/jxcore-log( 6698): 2016-01-11T14:48:12.092Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] failed
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:48:12.092Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] failed
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:48:12.093Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6698): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/bt-btif ( 2464): No ag scb for peer addr
,I/jxcore-log( 6698): 2016-01-11T14:48:17.093Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:48:17.094Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,D/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 6698): 2016-01-11T14:48:22.104Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:48:22.104Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:48:22.104Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:48:22.104Z SendDataConnector.js: do connect now
I/jxcore-log( 6698): 
I/io.jxcore.node.ConnectionHelper( 6698): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): connect: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 6698): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 824)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6698): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 6698): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2464): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnectionTimeout: [7C:F9:0E:34:8A:A0 S5-1]
I/jxcore-log( 6698): 2016-01-11T14:48:37.114Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] timed out
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:48:37.114Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] timed out
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:48:37.114Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6698): 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6698): 2016-01-11T14:48:42.124Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:48:42.124Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,D/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 6698): 2016-01-11T14:48:47.133Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:48:47.134Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:48:47.134Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:48:47.134Z SendDataConnector.js: do connect now
I/jxcore-log( 6698): 
I/io.jxcore.node.ConnectionHelper( 6698): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): connect: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 6698): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 826)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6698): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6698): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2464): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 c
,D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 9 c
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 8 c0
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): [1,452,523,728,127 ms] noteScanEnd no scan source
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=DISCONNECTED debouncing=false
,E/WifiStateMachine(  882): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiStateMachine(  882): CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  882): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  882): Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore(  882): will read network variables netId=0
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,I/wpa_supplicant( 1439): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
,D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1439): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiConfigStore(  882): setLastSelectedConfiguration -1
,E/wpa_supplicant( 1439): PNO: In assoc process
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=9304 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.056ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 20.246ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.851ms
,D/TCMD    (  480): NL - Read 312 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 192 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
I/wpa_supplicant( 1439): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1439): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1439): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
E/MDMCTBK (  294): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  294): get_freq !!, resp=2412
I/MDMCTBK (  294): get_freq !!, Strip data
I/MDMCTBK (  294): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
,I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1209713216
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
,I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
,W/ResourcesManager( 9304): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
E/WifiStateMachine(  882): Start Dhcp Watchdog 3
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  882): do suspend false
,E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1439): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ec93a73 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ec93a73 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1439): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  882): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: RESTARTING
D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  882): Killing 9188:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_9188/cgroup.procs: No such file or directory
,E/DHCPCD  ( 9338): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 9338): version 5.5.6 starting
,E/DHCPCD  ( 9338): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 9338): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 9338): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 9338): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 9338): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 9338): wlan0: sending REQUEST (xid 0x52e64158), next in 4.70 seconds
,I/DHCPCD  ( 9338): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 9338): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 9338): wlan0: adding IP address 192.168.1.123/24
,D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 20
D/TCMD    (  480): Listening for incoming client connection request
D/DHCPCD  ( 9338): wlan0: adding route to 192.168.1.0/24
,D/DHCPCD  ( 9338): wlan0: adding default route via 192.168.1.1
,D/DHCPCD  ( 9338): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 9338): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  882): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 102
E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  882): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  882):    accepting network in place of null
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/WifiP2pService(  882): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6698): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service request added successfully
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 14:48:51 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452523731294], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452523731276]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1534): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  882): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service discovery started successfully
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2591): now: 619929 ,futureTime: 9223372036854775807
D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2591): now: 619929 ,futureTime: 9223372036854775807
,D/PollingManager( 2591): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2591): now: 619930 ,futureTime: 9223372036854775807
D/OtaApp  ( 2591): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9411 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Central_PollingManager( 1465): now: 619989 ,futureTime: 86474724
D/Central_PollingManager( 1465): Polling alarm set to expire at: 86474724 Current Time: 619989
D/OtaApp  ( 2591): [debug] > PollingManagerService, now: 619989 ,futureTime: 5649973
D/OtaApp  ( 2591): [debug] > Polling alarm set to expire at: 5649973 Current Time: 619990
,D/MMApiProvisionService( 2591): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2591): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2591): createDeviceIdOrLogin update_device
,D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2591): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2591): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2591): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2591): createDeviceIdOrLogin update_device
D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2591): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 5550(282KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 646us total 28.407ms
,D/MMApiProvisionService( 2591): set mOutstandingReq to true.
,I/ Nonce  ( 2591):  Nonce getNonce 
,I/ Nonce  ( 2591):  Nonce Request 
I/ Nonce  ( 2591):  Nonce execute Request 
D/MMApiWebService( 2591): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2591): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2591): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2591): createDeviceIdOrLogin update_device
D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2591): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2591): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2591): [debug] > CusSM.onRadioUp
I/MusicStore( 9411): Database version: 120
D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2591): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2591): generating token using payload instead of using session token
,D/ Nonce  ( 2591):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2591): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9411): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9411): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9411): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9411): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9411): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9411): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9411): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9411): GMSCore installation verified
,I/ConfigStore( 9411): Config Database version: 1
,I/art     (  882): Explicit concurrent mark sweep GC freed 34174(1688KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.886ms total 120.344ms
,I/MediaRouter( 9411): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9411): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 9411): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 9411): type=WIFI subType= reason=null isConnected=true
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9462 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9411): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9411): Using platform SSLCertificateSocketFactory
,V/Mms     ( 9462): mnc/mcc: 
,V/Mms     ( 9462): tag: int value: recipientLimit - 20
V/Mms     ( 9462): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9462): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9462): tag: int value: maxSubjectLength - 80
V/Mms     ( 9462): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 9462): tag: bool value: enableGroupMms - false
V/Mms     ( 9462):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  882): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=9495 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9207:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_9207/cgroup.procs: No such file or directory
,W/ResourcesManager( 9495): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9495): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 9462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9515 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/MultiDex( 9495): VM with version 2.1.0 has multidex support
I/MultiDex( 9495): install
I/MultiDex( 9495): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  882): Killing 9227:android.process.acore/u0a7 (adj 15): empty #7
,D/PhoneMonitor( 9515): Register our PhoneStateListener
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_9227/cgroup.procs: No such file or directory
,D/WifiP2pService(  882): InactiveState{ when=-18ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-19ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/MobileConnectivityChangeReceiver( 9515): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 9515): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 9066:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9066/cgroup.procs: No such file or directory
,V/JNIHelp ( 9495): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9495): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9495): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@534c195: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9495): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 6698): Connected to the server!
I/jxcore-log( 6698): 
,I/chromium( 6698): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/NativeLibraryUtils( 9495): Install completed successfully. count=14 extracted=0
,I/CheckinService( 9495): Checkin interval check for package: unspecified last checkin: 1452523387574 min interval config: 0 actual interval: 347558
,I/CheckinService( 9495): Disabling old GoogleServicesFramework version
,I/CheckinService( 9495): Checking schedule, now: 1452523735161 next: 1452523417484
I/CheckinService( 9495): active receiver: enabled
,I/CheckinService( 9495): Preparing to send checkin request
,I/EventLogService( 9495): Accumulating logs since 1452523382256
,I/iu.SyncManager( 9495): SYNC; picasa accounts
,D/NetworkLogImpl( 9495): Loaded NetworkSpeedPredictor
,I/iu.Environment( 9495): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 9495): num queued entries: 0
,I/iu.UploadsManager( 9495): num updated entries: 0
,I/iu.SyncManager( 9495): NEXT; no task
,I/art     ( 9495): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9495): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9559 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/CheckinRequestBuilder( 9495): Checkin reason type: 8 attempt count: 1
,D/WifiService(  882): New client listening to asynchronous messages
,E/ActivityThread( 9495): Failed to find provider info for com.google.android.wearable.settings
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 1843(69KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 364us total 27.007ms
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9585 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9604 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 9604): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9604): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 9260): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 9304:com.motorola.context/u0a8 (adj 15): empty #7
,I/MultiDex( 9604): VM with version 2.1.0 has multidex support
I/MultiDex( 9604): install
,I/MultiDex( 9604): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_9304/cgroup.procs: No such file or directory
,V/JNIHelp ( 9604): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9585): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 9585): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9585):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9585):   adb logcat -s GAv4
,W/ContextImpl( 9585): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9585): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ActivityThread( 9604): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/GAv4    ( 9585): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9585): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/System  ( 9604): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9604): Installed default security provider GmsCore_OpenSSL
,W/GAv4    ( 9585): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/ Nonce  ( 2591):  Nonce Reponse 
,D/        ( 2591): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"13ad3542-e5f9-4bef-9a30-aa0571ee6488"}
D/MMApiWSBase( 2591): doRequest(): /v1/gdi/nonce.json resp length: 61
,W/GAv4    ( 9585): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ Nonce  ( 2591):  Nonce Handle Reponse 
D/MMApiProvisionService( 2591): mOutstandingReq set to false
I/art     ( 9604): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 9604): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 9604): Install completed successfully. count=14 extracted=0
,D/MMApiProvisionService( 2591):  pTime 1452467391223 sExp 172742 cTime 1452523736173 tTime 1452640133223
D/MMApiProvisionService( 2591):  No login Required 
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
,I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/art     (  882): Explicit concurrent mark sweep GC freed 11484(595KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.877ms total 116.094ms
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb13a4960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb7c23270, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c1d918, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c23e38, idLength=0xb12a4730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=285270839
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7b2a290
D/DrmWidevineDash(  296): message_length=1591, signature=0xb7c1d108, signature_length=2972337940
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/WebViewFactory( 9585): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9585): Time to load native libraries: 2 ms (timestamps 2583-2585)
I/LibraryLoader( 9585): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9585): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 9585): Expected native library version number "",actual native library version number ""
,I/chromium( 9585): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9585): Initializing chromium process, singleProcess=true
,W/art     ( 9585): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9585): ApplicationContext is null in ApplicationStatus
,W/chromium( 9585): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9585): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9585): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9585): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9585): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9585): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9585): Local Branch: 
I/Adreno-EGL( 9585): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9585): Local Patches: NONE
I/Adreno-EGL( 9585): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 92
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,W/DataUsage( 2591): invalid counter update blocked: 'err' by 0
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 ee
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 ee
D/Checkin ( 2591): publish the event [tag = MOT_CCE event name = LOG]
,W/AudioManagerAndroid( 9585): Requires BLUETOOTH permission
,I/NSApplication( 9585): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9671 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 9411:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/dex2oat ( 9688): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_9411/cgroup.procs: No such file or directory
,I/dex2oat ( 9688): dex2oat took 70.421ms (threads: 4)
,I/Adreno-EGL( 9604): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9604): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9604): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9604): Local Branch: 
I/Adreno-EGL( 9604): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9604): Local Patches: NONE
I/Adreno-EGL( 9604): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9697 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 9462:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 9604): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9604): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9604): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9604): Local Branch: 
I/Adreno-EGL( 9604): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9604): Local Patches: NONE
I/Adreno-EGL( 9604): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_9462/cgroup.procs: No such file or directory
,W/ResourcesManager( 9697): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb558e960
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb7b54be8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c1d918, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c23e78, idLength=0xb12a4730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=2429091622
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7b2a290
D/DrmWidevineDash(  296): message_length=1626, signature=0xb7c223f0, signature_length=2972337940
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9722 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9559:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/ContactLocale( 9722): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/ActivityManager(  882): Killing 9515:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9559/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2591): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_9515/cgroup.procs: No such file or directory
,I/WVCdm   (  296): CdmEngine::CloseSession
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,D/GetNotificationsWS( 2591): bindWebServices(): registering our AIDL callback...
I/SundryService( 2591): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2591): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2591): onServiceConnected()
D/GetNotificationsWS( 2591): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2591): unbindWebServices(): un-registering our AIDL callback...
I/PushService( 2591): started with background data enabled, making sure notification mechanism is enabled
D/OtaApp  ( 2591): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2591): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2591): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2591): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2591): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2591): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2591): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/LocationInitializer( 9495): Restart initialization of location
D/WearableService( 1737): callingUid 10016, callindPid: 1737
,D/AuthorizationBluetoothService( 1737): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1737): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno-EGL( 9604): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9604): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9604): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9604): Local Branch: 
I/Adreno-EGL( 9604): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9604): Local Patches: NONE
I/Adreno-EGL( 9604): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9758 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 20.924ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.298ms
,I/Adreno-EGL( 9604): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9604): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9604): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9604): Local Branch: 
I/Adreno-EGL( 9604): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9604): Local Patches: NONE
I/Adreno-EGL( 9604): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 19.859ms
,W/GCoreFlp( 1737): No location to return for getLastLocation()
,W/FusedLocationProvider( 1737): location=null
,W/IcingInternalCorpora( 9495): getNumBytesRead when not calculated.
,I/CheckinRequestBuilder( 9495): Classify the device as Phone.
,I/ActivityManager(  882): Killing 9585:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/CheckinTask( 9495): Sending checkin request (9556 bytes)
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_9585/cgroup.procs: No such file or directory
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-34
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
E/MDM     ( 1737): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 9495): Restart initialization of location
,D/AuthorizationBluetoothService( 1737): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/GLSActivity( 1737): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1737): No location to return for getLastLocation()
W/FusedLocationProvider( 1737): location=null
,I/CheckinRequestBuilder( 9495): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 9495): Failed to find provider info for com.google.android.wearable.settings
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/CheckinRequestBuilder( 9495): Classify the device as Phone.
,I/CheckinTask( 9495): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 9495): Checking schedule, now: 1452523738995 next: 1453124875989
,I/CheckinService( 9495): active receiver: disabled
,D/CheckinService( 9495): Recording last checkin time for package unspecified as 1452523739008
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9805 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 9805): Register our PhoneStateListener
,V/SetupWizard( 9805): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 9671:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_9671/cgroup.procs: No such file or directory
,D/GCM     ( 1737): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 92
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnectionTimeout: [7C:F9:0E:34:8A:A0 S5-1]
I/jxcore-log( 6698): 2016-01-11T14:49:02.146Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] timed out
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:49:02.147Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] timed out
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:49:02.147Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6698): 
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 ee
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 ee
,I/ActivityManager(  882): Killing 9697:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_9697/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 9722:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_9722/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 7e
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 7e
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-40
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6698): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service request added successfully
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=9845 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3aae27f5
,I/GCoreNlp( 1737): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/art     (  882): Explicit concurrent mark sweep GC freed 17909(937KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.531ms total 127.491ms
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service discovery started successfully
,I/Launcher( 1571): Deferring update until onResume
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9875 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=9894 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9758:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9758/cgroup.procs: No such file or directory
,W/ResourcesManager( 9260): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9260): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9260): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,W/System  ( 9260): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9260): Installed default security provider GmsCore_OpenSSL
,I/ContactLocale( 9894): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9917 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9805:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_9805/cgroup.procs: No such file or directory
,W/asset   ( 9917): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 9917): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9917): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9917): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 9845): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
D/PackageBroadcastService( 9495): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9941 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 9495): Null package name or gms related package.  Ignoreing.
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP a2:39:
D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/UpdateIcingCorporaServi( 9845): UpdateCorporaTask done [took 124 ms] updated apps [took 124 ms] 
W/ResourcesManager( 9941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 9495): Storage manager: low false usage 1.73MB avail 3.12GB capacity 4.85GB
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP ee:1f:
D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9975 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 9495): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  882): Killing 9604:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_9604/cgroup.procs: No such file or directory
,D/Finsky  ( 9975): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 9495): Internal init done: storage state 0
,I/Icing   ( 9495): Post-init done
,I/Icing   ( 9495): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 9975): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 9975): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 9975): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 9975): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 9975): Skipping gmscore version check
D/Finsky  ( 9975): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 9975): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 9975): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 9875:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_9875/cgroup.procs: No such file or directory
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,I/jxcore-log( 6698): 2016-01-11T14:49:07.149Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:49:07.155Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/Icing   ( 9495): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 9495): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 9495): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 9917:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_9917/cgroup.procs: No such file or directory
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-34
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/ActivityManager(  882): Killing 9260:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_9260/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-56
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -56 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -56 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,E/bt-btif ( 2464): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2464): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 822)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Maximum number of allowed retries (0) reached, giving up... (thread ID: 822)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Exiting thread (thread ID: 822)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): shutdown (thread ID: 822)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 6698): 2016-01-11T14:49:12.160Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:49:12.160Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:49:12.160Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:49:12.161Z SendDataConnector.js: do connect now
I/jxcore-log( 6698): 
I/io.jxcore.node.ConnectionHelper( 6698): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): connect: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 6698): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6698): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 828)
,W/BluetoothAdapter( 6698): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2464): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/CheckinService( 9495): Done disabling old GoogleServicesFramework version
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310185, SEQNUM=4610, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1334, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,I/jxcore-log( 6698): timeout now
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): weAreDoneNow, resultArray.length: 0
I/jxcore-log( 6698): 
I/jxcore-log( 6698): sendReportNow
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): done, now sending data to server
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:49:18.725Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6698): 
D/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
E/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 6698): 2016-01-11T14:49:18.726Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6698): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service request added successfully
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 1439): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1439): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service discovery started successfully
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,I/wpa_supplicant( 1439): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,D/io.jxcore.node.ConnectionHelper( 6698): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6698): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 6698): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  294): Event received = P2P-SERV-DISC-REQ 2437 92
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): onConnectionTimeout: [7C:F9:0E:34:8A:A0 S5-1]
I/jxcore-log( 6698): 2016-01-11T14:49:27.169Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] timed out
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:49:27.170Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:34:8A:A0 S5-1] timed out
I/jxcore-log( 6698): 
I/jxcore-log( 6698): oneRoundDownNow
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): 2016-01-11T14:49:27.171Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6698): 
,D/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6698): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6698): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 6698): 2016-01-11T14:49:27.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6698): 
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310717, SEQNUM=4612, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1374, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2464): Disconnected process message: 10, size: 0
,I/jxcore-log( 6698): teardown
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): testSendData stopped
I/jxcore-log( 6698): 
,I/io.jxcore.node.ConnectionHelper( 6698): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6698): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6698): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6698): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6698): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6698): stop: Stopping services
,D/WifiP2pService(  882): InactiveState{ when=0 what=139298 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139298 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): stop: Stopping P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1439): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1439): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
D/WifiP2pService(  882): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): setState: NOT_INITIALIZED
D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
D/WifiP2pService(  882): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6698): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6698): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6698): setState: NOT_STARTED
I/jxcore-log( 6698): StopBroadcasting went ok
I/jxcore-log( 6698): 
I/jxcore-log( 6698): 2016-01-11T14:49:38.447Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6698): 
I/chromium( 6698): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6698): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6698): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6698): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6698): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6698): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 6698): ****TEST TOOK:  ms ****
I/jxcore-log( 6698): 
,I/jxcore-log( 6698): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6698): 
,D/AndroidRuntime(10041): 
D/AndroidRuntime(10041): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10041): CheckJNI is OFF
,D/AndroidRuntime(10041): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10436 user=-1: uninstall pkg
,I/ActivityManager(  882): Killing 6698:com.test.thalitest/u0a436 (adj 9): stop com.test.thalitest
,I/WindowState(  882): WIN DEATH: Window{1a12506a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  882): Client connection lost with reason: 4
,W/PackageSettings(  882): Skipping PackageSetting{f36067b com.example.hello/10426} due to missing metadata
,E/bt-btif ( 2464): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:8, channel:1
,E/bt-btif ( 2464): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:9, channel:1
,E/bt-btif ( 2464): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:10, channel:-1
,I/ActivityManager(  882):   Force finishing activity ActivityRecord{1661a57 u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  882): Spurious death for ProcessRecord{2a2289cb 6698:com.test.thalitest/u0a436}, curProc for 6698: null
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10436 user=0: pkg removed
,I/art     ( 3000): Explicit concurrent mark sweep GC freed 11367(2MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 7MB/12MB, paused 1.077ms total 34.514ms
,I/art     ( 1571): Explicit concurrent mark sweep GC freed 5420(330KB) AllocSpace objects, 7(353KB) LOS objects, 24% free, 13MB/17MB, paused 489us total 51.875ms
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1737): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1422): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1422): run()
,I/Decoder ( 1422): createOrResetDecoder
,D/VoicemailCleanupService( 9894): Cleaning up data for package: com.test.thalitest
,I/LaunchCheckinHandler(  882): cleanup(): cleared. Last call was 33463 ms ago
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10067 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  882): Explicit concurrent mark sweep GC freed 23047(1566KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.442ms total 136.221ms
I/art     (  882): WaitForGcToComplete blocked for 98.672ms for cause Explicit
,I/ConfigService( 1737): onCreate
,W/asset   (10067): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10067): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10067): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10067): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1422): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1422): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1422): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1422): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1422): run()
I/StatsUtilsManager( 1422): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1422): shouldRecordStats() = Too Soon
,I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10095 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  882): removeObsoleteFile: deleting file=3_task.xml
,I/ActivityManager(  882): Killing 9845:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  882): Explicit concurrent mark sweep GC freed 6354(365KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.342ms total 235.695ms
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_9845/cgroup.procs: No such file or directory
,W/ContextImpl(10095): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 9495): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/Launcher( 1571): Deferring update until onResume
,D/ChimeraCfgMgr( 9495): Reading stored module config
,D/AccountUtils( 9495): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 9495): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 9495): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 9495): Removing dialog suppression flag for package com.test.thalitest
,D/AndroidRuntime(10041): Shutting down VM
,I/GMPM-SVC( 9495): App measurement is starting up, version: 8489
I/GMPM-SVC( 9495): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1737): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1737): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 9495): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 9495): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 9495): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 9495): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 9495): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 9495): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 9495): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 9495): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 9495): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 9495): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 9495): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 9495): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 9495): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=10125 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 9495): doRemovePackageData com.test.thalitest
,D/ChimeraCfgMgr( 9495): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 9495): Module APK com.google.android.play.games already loaded
,W/BaseAppContext( 9495): Using Auth Proxy for data requests.
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:29000 mC
,E/ConnectivityChangeReceiver( 9495): Ignoring connectivity change
,E/BaseAppContext( 9495): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 9495): Using Auth Proxy for data requests.
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,D/ConnectivityService(  882): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  882): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  882): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 9495): CM callback handler got msg 524290
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=10162 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.151ms
,W/BaseAppContext( 9495): Using Auth Proxy for data requests.
W/BaseAppContext( 9495): Using Auth Proxy for data requests.
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 19.825ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 20.647ms
,W/BaseAppContext( 9495): Using Auth Proxy for data requests.
,W/BaseAppContext( 9495): Using Auth Proxy for data requests.
,W/BaseAppContext( 9495): Using Auth Proxy for data requests.
W/BaseAppContext( 9495): Using Auth Proxy for data requests.
,W/BaseAppContext( 9495): Using Auth Proxy for data requests.
,W/DriveInitializer( 9495): Awaiting to be initialized
,W/DriveInitializer( 9495): Background init thread started
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10188 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi(10125): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  882): Killing 9941:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9495): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_9941/cgroup.procs: No such file or directory
,E/SQLiteLog( 9495): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 9495): (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 9495): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 9495): Process: com.google.android.gms, PID: 9495
E/AndroidRuntime( 9495): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 9495): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 9495): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 9495): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 9495): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 9495): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 9495): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 9495): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 9495): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 9495): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 9495): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 9495): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 9495): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 9495): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 9495): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DocListDatabase( 9495): Failed to delete from FileContent163 table
E/DocListDatabase( 9495): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 9495): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 9495): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 9495): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 9495): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 9495): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 9495): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 9495): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 9495): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 9495): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 9495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 9495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 9495): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 9495): Sending signal. PID: 9495 SIG: 9
,E/DropBoxManagerService(  882): Can't write: system_app_crash
E/DropBoxManagerService(  882): java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  882): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  882): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  882): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  882): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  882): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  882): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  882): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  882): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  882): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  882): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  882): 	... 5 more
,D/ConnectivityService(  882): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2cbeca1a)
D/ConnectivityService(  882): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiService(  882): Client connection lost with reason: 4
E/ConnectivityService(  882): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
E/AppDataSearchHelper(10125): Couldn't fetch status for corpus applications_uri
W/AppDataSearchHelper(10125): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi(10125): UpdateCorporaTask done [took 267 ms] updated apps [took 266 ms] 

```
