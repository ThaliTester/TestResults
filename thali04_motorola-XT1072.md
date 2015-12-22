#### Test 543122982543be8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:33000 mC
D/AndroidRuntime( 6523): 
D/AndroidRuntime( 6523): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6523): CheckJNI is OFF
D/AndroidRuntime( 6523): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6542 uid=10402 gids={50402, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6523): Shutting down VM
I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.932ms
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 22.390ms
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 26.075ms
,I/WebViewFactory( 6542): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6542): Time to load native libraries: 19 ms (timestamps 7382-7401)
I/LibraryLoader( 6542): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6542): Binding Chromium to main looper Looper (main, tid 1) {27c8289}
,I/LibraryLoader( 6542): Expected native library version number "",actual native library version number ""
,I/chromium( 6542): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6542): Initializing chromium process, singleProcess=true
,W/art     ( 6542): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6542): ApplicationContext is null in ApplicationStatus
,W/chromium( 6542): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6542): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6542): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6542): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6542): Local Branch: 
I/Adreno-EGL( 6542): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6542): Local Patches: NONE
I/Adreno-EGL( 6542): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{3747a280 u0 com.test.thalitest/.MainActivity t3}
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c674198:true
,W/art     ( 6542): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6542): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6542): CordovaWebView is running on device made by: motorola
,W/art     ( 6542): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6542): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  882): Explicit concurrent mark sweep GC freed 29102(1450KB) AllocSpace objects, 2(214KB) LOS objects, 33% free, 20MB/30MB, paused 1.835ms total 138.232ms
D/OpenGLRenderer( 6542): Render dirty regions requested: true
,D/Atlas   ( 6542): Validating map...
,W/chromium( 6542): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6542): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6542): Enabling debug mode 0
,I/Keyboard.Facilitator( 1416): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1128
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +1s31ms (total +1s128ms)
,W/IInputConnectionWrapper( 6542): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6542): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6542): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6542): Cannot call determinedVisibility() - never saw a connection for the pid: 6542
,D/JsMessageQueue( 6542): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6542): JniHelper::setJavaVM(0xb8eee310), pthread_self() = -1189666768
,D/JX-Cordova( 6542): jxcore cordova android initializing
,W/jxcore-log( 6542): Initializing JXcore engine
W/jxcore-log( 6542): JXcore engine is ready
,W/jxcore-log( 6542): Starting JXcore engine
,W/.test.thalitest( 6542): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10402 path="socket:[9339]" dev="sockfs" ino=9339 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6542): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10402 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6542): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10402 path="socket:[6620]" dev="sockfs" ino=6620 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6542): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10402 path="socket:[29455]" dev="sockfs" ino=29455 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6542): Platform android
W/jxcore-log( 6542): 
,W/jxcore-log( 6542): Process ARCH arm
W/jxcore-log( 6542): 
,I/jxcore-log( 6542): JXcore Cordova bridge is ready!
I/jxcore-log( 6542): 
,W/jxcore-log( 6542): JXcore engine is started
I/Choreographer( 6542): Skipped 172 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6542): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310786, SEQNUM=4435, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12520, POWER_SUPPLY_CHARGE_COUNTER=-424, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/jxcore-log( 6542): Toggling radios to true
I/jxcore-log( 6542): 
,D/BluetoothAdapter( 6542): enable(): BT is already enabled..!
,D/WifiService(  882): New client listening to asynchronous messages
,D/WifiService(  882): setWifiEnabled: true pid=6542, uid=10402
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6542): Radios toggled
I/jxcore-log( 6542): 
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6542): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): Perf Test app loaded loaded
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): check test folder
I/jxcore-log( 6542): 
I/jxcore-log( 6542): found test : ./testFindPeers.js
I/jxcore-log( 6542): 
,I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  298):  STA Disconnected !!
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  298): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  475): NL - Read 1004 bytes from update socket.
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
D/TCMD    (  475): NL - message type is RTM_NEWLINK
I/MDMCTBK (  298): set_property_value, Exit
D/TCMD    (  475): Listening for incoming client connection request
E/MDMCTBK (  298): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  298): Event received = CTRL-EVENT-REGDOM-CHANGE
I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  298): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  882): InitialState.processMessage what=4
E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882):  0
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/jxcore-log( 6542): found test : ./testSendData.js
I/jxcore-log( 6542): 
,D/CommandListener(  295): Clearing all IP addresses on wlan0
,D/TCMD    (  475): NL - Read 60 bytes from update socket.
D/TCMD    (  475): NL - ignore NL message, type = 21
D/TCMD    (  475): Listening for incoming client connection request
,V/NativeCrypto( 1759): Read error: ssl=0xb91e8b68: I/O error during system call, Connection timed out
,V/NativeCrypto( 1759): SSL shutdown failed: ssl=0xb91e8b68: I/O error during system call, Broken pipe
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,I/jxcore-log( 6542): found test : ./testSendData2.js
I/jxcore-log( 6542): 
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  882): connected time updated 114142
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6621 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  882): Start Disconnecting Watchdog 1
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/ConnectivityManager.CallbackHandler( 1954): CM callback handler got msg 524292
I/ModemStatsDSDetect( 1519): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/CommandListener(  295): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1519): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1519): onReceive() - done, currentInetCondition=0
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1519): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/ModemStatsDSDetect( 1519): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1519): onReceive() - done, currentInetCondition=0
E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
W/ResourcesManager( 6621): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
I/Choreographer( 6542): Skipped 125 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6542): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6648 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6335:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_6335/cgroup.procs: No such file or directory
,W/ResourcesManager( 6648): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6648): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6648): MmsConfig.loadMmsSettings
I/Babel_SMS( 6648): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6648): MmsConfig.loadFromDatabase
,I/wpa_supplicant( 1437): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1437): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiStateMachine(  882): [1,450,745,532,730 ms] noteScanEnd no scan source
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  298): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  298): Event received = Trying to associate with
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@459962d sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Babel_SMS( 6648): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6648): MmsConfig.loadFromResources
,E/Babel_SMS( 6648): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6648): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6648): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6648): startup - clean
,I/Babel   ( 6648): deleted: false for 0
,D/TCMD    (  475): NL - Read 312 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 192 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 1004 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/TCMD    (  475): NL - Read 80 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 80 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
I/wpa_supplicant( 1437): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  298): Event received = Associated with c0:ff:d4
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1437): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  298): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  298): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  298):  STA Connected !!
,D/TCMD    (  475): NL - Read 1004 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/MDMCTBK (  298): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  298): get_freq !!, resp=2412
I/MDMCTBK (  298): get_freq !!, Strip data
I/MDMCTBK (  298): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
,I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  298): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  298): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  298): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1215267096
I/MDMCTBK (  298): return from set_get_from_wpa_supplicant
I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  298): set_property_value, Enter
D/MDMCTBK (  298): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
E/MDMCTBK (  298): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  298): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  298): , reply_len: 3, ret: 0
E/MDMCTBK (  298): MdmCutbackHndler, resp=OK
E/MDMCTBK (  298): 
D/MDMCTBK (  298): wifi_set_tx_pwr: Exit
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  295): Setting iface cfg
,E/WifiStateMachine(  882): Start Dhcp Watchdog 2
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  882): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@311b95d5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@311b95d5 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6648): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6648): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6648): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6648): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6648): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6648): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6648): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6648): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 5989:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_5989/cgroup.procs: No such file or directory
,I/vclib   ( 6648): onServiceConnected
W/Babel   ( 6648): Attempted to change video mute state without an active call.
,E/DHCPCD  ( 6686): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 6686): version 5.5.6 starting
,E/DHCPCD  ( 6686): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6686): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6686): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6686): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6686): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6686): wlan0: sending REQUEST (xid 0x447b630c), next in 4.47 seconds
,I/DHCPCD  ( 6686): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6686): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6686): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6686): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6686): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6686): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  475): NL - Read 60 bytes from update socket.
D/TCMD    (  475): NL - ignore NL message, type = 20
D/TCMD    (  475): Listening for incoming client connection request
,D/DHCPCD  ( 6686): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  882): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  882): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882):    accepting network in place of null
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1519): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/ModemStatsDSDetect( 1519): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1519): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1954): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Dec 2015 00:52:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450745534747], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450745534726]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
,D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1954): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1519): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1519): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1519): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1519): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:33000 mC
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2581): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6758 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1474): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2581): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2581): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2581): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2581): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2581): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2581): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2581): [debug] > CusSM.onRadioDown
,D/CCE     ( 2581): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2581): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2581): Registering with Alarm Manager to restart CCE
,I/MusicStore( 6758): Database version: 120
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6758): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/ConnectivityService(  882): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1954): CM callback handler got msg 524295
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6758): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6758): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6758): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6758): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6758): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6758): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6758): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b19ac75: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6758): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6758): GMSCore installation verified
,I/ConfigStore( 6758): Config Database version: 1
,I/MediaRouter( 6758): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6758): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6758): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6758): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6805 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6758): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6758): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 6380:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_6380/cgroup.procs: No such file or directory
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,V/Mms     ( 6805): mnc/mcc: 
V/Mms     ( 6805): tag: int value: recipientLimit - 20
,V/Mms     ( 6805): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6805): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6805): tag: int value: maxSubjectLength - 80
V/Mms     ( 6805): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6805): tag: bool value: enableGroupMms - false
V/Mms     ( 6805):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6805): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6831 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6412:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_6412/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6831): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6831): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6831): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 6648:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6648/cgroup.procs: No such file or directory
,I/CheckinService( 1954): Checkin interval check for package: unspecified last checkin: 1450745461839 min interval config: 0 actual interval: 74624
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6853 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1954): Checking schedule, now: 1450745536514 next: 1450745491818
I/CheckinService( 1954): active receiver: enabled
,I/CheckinService( 1954): Preparing to send checkin request
I/EventLogService( 1954): Accumulating logs since 1450745458920
,I/CheckinRequestBuilder( 1954): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1954): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  882): Explicit concurrent mark sweep GC freed 47366(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.794ms total 124.444ms
,V/GLSActivity( 1759): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1759): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6876 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6896 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6876): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6876): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6896): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 6876): VM with version 2.1.0 has multidex support
I/MultiDex( 6876): install
I/MultiDex( 6876): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6876): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6876): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6876): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@218c152: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6876): Installed default security provider GmsCore_OpenSSL
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6542): BLE supported!!
I/jxcore-log( 6542): 
,I/art     ( 6876): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6876): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 6896): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6896): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6896): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6896): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6896): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6896): MmsConfig.loadFromResources
,E/Babel_SMS( 6896): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6896): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 6876): Install completed successfully. count=14 extracted=0
,W/Settings( 6896): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6896): startup - clean
,I/Babel   ( 6896): deleted: false for 0
,D/WVCdm   (  300): Instantiating CDM.
,I/WVCdm   (  300): CdmEngine::OpenSession
,I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee5000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee5000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xbede04e0
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb8cdfad0, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8cdd2c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6937 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e2a7a0, idLength=0xb551e730
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=2678265777
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8ce3a80
D/DrmWidevineDash(  300): message_length=1591, signature=0xb8ce40c0, signature_length=3042043668
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2581): now: 188893 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  882): MasterInitialState.processMessage what=3
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2581): now: 188896 ,futureTime: 9223372036854775807
D/PollingManager( 2581): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2581): now: 188896 ,futureTime: 9223372036854775807
D/OtaApp  ( 2581): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1474): now: 188897 ,futureTime: 86473520
D/Central_PollingManager( 1474): Polling alarm set to expire at: 86473520 Current Time: 188897
,D/OtaApp  ( 2581): [debug] > PollingManagerService, now: 188902 ,futureTime: 37302969
D/OtaApp  ( 2581): [debug] > Polling alarm set to expire at: 37302969 Current Time: 188902
,I/NetworkMonitor( 6758): type=WIFI subType= reason=null isConnected=true
,W/VideoCapabilities( 6896): Unrecognized profile 2130706433 for video/avc
D/MMApiProvisionService( 2581): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2581): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2581): createDeviceIdOrLogin update_device
,D/Checkin ( 2581): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2581): Not proxy app, so login/provision not allowed
,W/AudioCapabilities( 6896): Unsupported mime audio/amr-wb-plus
,D/MMApiProvisionService( 2581): isDeviceProvisioned: deviceId = 2072049230914535424
,W/VideoCapabilities( 6896): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6896): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6896): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6896): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6896): Unrecognized profile 2130706433 for video/avc
,I/art     ( 2581): Explicit concurrent mark sweep GC freed 17046(921KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.058ms total 91.931ms
,D/CCE     ( 2581): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2581): createDeviceIdOrLogin update_device
D/Checkin ( 2581): publish the event [tag = MOT_CCE event name = LOG]
,W/VideoCapabilities( 6896): Unrecognized profile 2130706433 for video/avc
,D/MMApiProvisionService( 2581): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2581): set mOutstandingReq to true.
I/ Nonce  ( 2581):  Nonce getNonce 
I/ Nonce  ( 2581):  Nonce Request 
I/ Nonce  ( 2581):  Nonce execute Request 
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,D/MMApiWebService( 2581): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,I/vclib   ( 6896): onServiceConnected
W/Babel   ( 6896): Attempted to change video mute state without an active call.
,D/MMApiProvisionService( 2581): isDeviceProvisioned: deviceId = 2072049230914535424
,I/dex2oat ( 6954): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/CCE     ( 2581): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2581): createDeviceIdOrLogin update_device
D/Checkin ( 2581): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2581): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2581): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2581): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2581): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2581): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2581): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2581): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2581): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2581): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2581): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/Babel   ( 6896): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 6621:com.motorola.context/u0a8 (adj 15): empty #7
,D/MMApiWebService( 2581): generating token using payload instead of using session token
,D/ Nonce  ( 2581):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2581): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2581): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_6621/cgroup.procs: No such file or directory
,I/dex2oat ( 6954): dex2oat took 225.662ms (threads: 4)
,I/Adreno-EGL( 6876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6876): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6876): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6876): Local Branch: 
I/Adreno-EGL( 6876): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6876): Local Patches: NONE
I/Adreno-EGL( 6876): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6937): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6937): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6937): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6937): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6937): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6937):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6937):   adb logcat -s GAv4
,W/GAv4    ( 6937): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6876): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6876): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6876): Local Branch: 
I/Adreno-EGL( 6876): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6876): Local Patches: NONE
I/Adreno-EGL( 6876): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 6937): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6937): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  300): CdmEngine::OpenSession
,I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee5000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee5000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xbede04e0
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb8cf4a88, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8cdd2c8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e2a7e0, idLength=0xb551e730
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=3745932856
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8ce3a80
,D/DrmWidevineDash(  300): message_length=1626, signature=0xb8ce40e0, signature_length=3042043668
,I/WebViewFactory( 6937): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6937): Time to load native libraries: 2 ms (timestamps 9795-9797)
I/LibraryLoader( 6937): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6937): Binding Chromium to main looper Looper (main, tid 1) {6b02302}
I/LibraryLoader( 6937): Expected native library version number "",actual native library version number ""
I/chromium( 6937): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6937): Initializing chromium process, singleProcess=true
W/art     ( 6937): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6937): ApplicationContext is null in ApplicationStatus
,W/chromium( 6937): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6937): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6937): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6937): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6937): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6937): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6937): Local Branch: 
I/Adreno-EGL( 6937): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6937): Local Patches: NONE
I/Adreno-EGL( 6937): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 6937): Requires BLUETOOTH permission
,I/NSApplication( 6937): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7013 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6758:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_6758/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6876): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6876): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6876): Local Branch: 
I/Adreno-EGL( 6876): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6876): Local Patches: NONE
I/Adreno-EGL( 6876): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6876): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6876): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6876): Local Branch: 
I/Adreno-EGL( 6876): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6876): Local Patches: NONE
I/Adreno-EGL( 6876): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7033 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 6805:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 23.401ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.602ms
,I/CheckinRequestBuilder( 1954): Classify the device as Phone.
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.022ms
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_6805/cgroup.procs: No such file or directory
,I/ Nonce  ( 2581):  Nonce Reponse 
D/        ( 2581): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"1a221d92-8fbd-4b24-9b72-01ad67cb39bc"}
D/MMApiWSBase( 2581): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2581):  Nonce Handle Reponse 
D/MMApiProvisionService( 2581): mOutstandingReq set to false
,W/ResourcesManager( 7033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1474): Explicit concurrent mark sweep GC freed 55751(3MB) AllocSpace objects, 37(1323KB) LOS objects, 39% free, 7MB/12MB, paused 975us total 46.493ms
,D/MMApiProvisionService( 2581):  pTime 1450652997779 sExp 172742 cTime 1450745539409 tTime 1450825739779
D/MMApiProvisionService( 2581):  No login Required 
I/CheckinTask( 1954): Sending checkin request (9511 bytes)
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7057 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ContactLocale( 7057): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  882): Explicit concurrent mark sweep GC freed 12352(579KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.848ms total 143.086ms
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7080 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6853:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/CheckinRequestBuilder( 1954): Checkin reason type: 8 attempt count: 1
,W/DataUsage( 2581): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2581): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  882): Killing 6831:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_6853/cgroup.procs: No such file or directory
,E/ActivityThread( 1954): Failed to find provider info for com.google.android.wearable.settings
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_6831/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1954): Classify the device as Phone.
,I/MusicStore( 7080): Database version: 120
,I/CheckinTask( 1954): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1954): Checking schedule, now: 1450745540014 next: 1451346677008
I/CheckinService( 1954): active receiver: disabled
,D/CheckinService( 1954): Recording last checkin time for package unspecified as 1450745540055
,I/ActivityManager(  882): Killing 6937:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ActivityManager(  882): Killing 6896:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_6937/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6896/cgroup.procs: No such file or directory
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7080): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7080): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7080): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7080): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7080): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7080): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7080): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7080): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b19ac75: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7080): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7080): GMSCore installation verified
,I/ConfigStore( 7080): Config Database version: 1
,I/MediaRouter( 7080): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7080): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7080): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7080): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7114 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6433): Explicit concurrent mark sweep GC freed 1570(68KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 365us total 30.994ms
,I/GHttpClientFactory( 7080): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7080): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 7013:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7114): mnc/mcc: 
,V/Mms     ( 7114): tag: int value: recipientLimit - 20
V/Mms     ( 7114): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7114): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7114): tag: int value: maxSubjectLength - 80
V/Mms     ( 7114): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7114): tag: bool value: enableGroupMms - false
V/Mms     ( 7114):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7013/cgroup.procs: No such file or directory
,W/ResourcesManager( 7114): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7149 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7033:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7033/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7149): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7149): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7149): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 7057:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7057/cgroup.procs: No such file or directory
,I/CheckinService( 1954): Checkin interval check for package: unspecified last checkin: 1450745540055 min interval config: 0 actual interval: 960
,I/CheckinService( 1954): Checking schedule, now: 1450745541022 next: 1450745570008
I/CheckinService( 1954): active receiver: disabled
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7171 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7191 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7080:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7080/cgroup.procs: No such file or directory
,W/ResourcesManager( 7191): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7191): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7191): MmsConfig.loadMmsSettings
I/Babel_SMS( 7191): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7191): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7191): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7191): MmsConfig.loadFromResources
,E/Babel_SMS( 7191): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7191): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,V/AlarmManager(  882): send {1a28d668, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  882): send {bc22c3a, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/Settings( 7191): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7191): startup - clean
,V/AlarmManager(  882): done {1a28d668, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/Babel   ( 7191): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7226 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7191): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7191): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7191): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7191): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7191): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7191): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7191): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7191): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7191): onServiceConnected
W/Babel   ( 7191): Attempted to change video mute state without an active call.
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7226): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7226): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7226):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7226):   adb logcat -s GAv4
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7226): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7226): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7226): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7226): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7191): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 7114:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7226): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7226): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7114/cgroup.procs: No such file or directory
,I/WebViewFactory( 7226): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/global frequency( 2581): no tags to log
D/Checkin ( 2581): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2581): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/LibraryLoader( 7226): Time to load native libraries: 2 ms (timestamps 3610-3612)
I/LibraryLoader( 7226): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7226): Binding Chromium to main looper Looper (main, tid 1) {6b02302}
I/LibraryLoader( 7226): Expected native library version number "",actual native library version number ""
,I/chromium( 7226): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7226): Initializing chromium process, singleProcess=true
W/art     ( 7226): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7226): ApplicationContext is null in ApplicationStatus
,W/chromium( 7226): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7226): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7226): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7226): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7226): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7226): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7226): Local Branch: 
I/Adreno-EGL( 7226): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7226): Local Patches: NONE
I/Adreno-EGL( 7226): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7226): Requires BLUETOOTH permission
,I/art     (  882): Explicit concurrent mark sweep GC freed 11370(573KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.828ms total 131.541ms
,I/NSApplication( 7226): Starting up...
,D/BSUtils ( 2581): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2581): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7296 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7149:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7149/cgroup.procs: No such file or directory
,D/BSUtils ( 2581): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1474): Explicit concurrent mark sweep GC freed 4232(176KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 551us total 27.231ms
,D/BSUtils ( 2581): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2581): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7320 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7171:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7171/cgroup.procs: No such file or directory
,W/ResourcesManager( 7320): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/BSUtils ( 2581): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2581): Explicit concurrent mark sweep GC freed 13469(808KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/18MB, paused 1.029ms total 67.368ms
,D/BSUtils ( 2581): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2581): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2581): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2581): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2581): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2581): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2581): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2581): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2581): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2581): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2581): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7340 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7226:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7340): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7191:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7226/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7191/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2581): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2581): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2581): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2581): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2581): onServiceConnected()
,D/GetNotificationsWS( 2581): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2581): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2581): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7376 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.213ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.566ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.239ms
,D/WearableService( 1759): callingUid 10016, callindPid: 1759
,D/LocationInitializer( 1954): Restart initialization of location
,D/AuthorizationBluetoothService( 1759): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1759): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     (  882): Explicit concurrent mark sweep GC freed 6940(302KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.425ms total 125.820ms
,V/GLSActivity( 1759): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7405 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,W/FusedLocationProvider( 1759): location=null
,I/MusicStore( 7405): Database version: 120
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7405): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7405): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7405): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,V/AlarmManager(  882): send {3d1838ff, *walarm*:com.google.android.intent.action.SEND_IDLE}
,W/ResourcesManager( 7405): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7405): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7405): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7405): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7405): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b19ac75: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7405): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7405): GMSCore installation verified
,I/ConfigStore( 7405): Config Database version: 1
,I/MediaRouter( 7405): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7405): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7405): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7405): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7437 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7405): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7405): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 7296:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7437): mnc/mcc: 
,V/Mms     ( 7437): tag: int value: recipientLimit - 20
V/Mms     ( 7437): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7437): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7437): tag: int value: maxSubjectLength - 80
V/Mms     ( 7437): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7437): tag: bool value: enableGroupMms - false
V/Mms     ( 7437):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7296/cgroup.procs: No such file or directory
,W/ResourcesManager( 7437): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7463 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7320:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7463): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7320/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7463): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7463): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 7340:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7340/cgroup.procs: No such file or directory
,I/CheckinService( 1954): Checkin interval check for package: unspecified last checkin: 1450745540055 min interval config: 0 actual interval: 4857
,I/CheckinService( 1954): Checkin interval check for package: unspecified last checkin: 1450745540055 min interval config: 0 actual interval: 4861
,I/CheckinService( 1954): Checking schedule, now: 1450745544926 next: 1450745570008
I/CheckinService( 1954): active receiver: disabled
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7489 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/CheckinService( 1954): Checking schedule, now: 1450745545001 next: 1450745570008
,I/CheckinService( 1954): active receiver: disabled
,W/ResourcesManager( 7489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7489): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7489): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7489): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7489): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7489): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7489): MmsConfig.loadFromResources
,E/Babel_SMS( 7489): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7489): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:34000 mC
,W/Settings( 7489): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7489): startup - clean
,I/Babel   ( 7489): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7523 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7489): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7489): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7489): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7523): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 7523): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7523):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7523):   adb logcat -s GAv4
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7523): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7523): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
I/vclib   ( 7489): onServiceConnected
W/ContextImpl( 7523): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/Babel   ( 7489): Attempted to change video mute state without an active call.
,W/GAv4    ( 7523): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7523): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7523): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7489): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 6876:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_6876/cgroup.procs: No such file or directory
,I/WebViewFactory( 7523): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7523): Time to load native libraries: 2 ms (timestamps 7177-7179)
,I/LibraryLoader( 7523): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7523): Binding Chromium to main looper Looper (main, tid 1) {6b02302}
,I/LibraryLoader( 7523): Expected native library version number "",actual native library version number ""
,I/chromium( 7523): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7523): Initializing chromium process, singleProcess=true
,W/art     ( 7523): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7523): ApplicationContext is null in ApplicationStatus
,W/chromium( 7523): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7523): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7523): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7523): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7523): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7523): Local Branch: 
I/Adreno-EGL( 7523): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7523): Local Patches: NONE
I/Adreno-EGL( 7523): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7523): Requires BLUETOOTH permission
I/NSApplication( 7523): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7588 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7405:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7405/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7607 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7437:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7437/cgroup.procs: No such file or directory
,W/ResourcesManager( 7607): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7627 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Killing 7376:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ContactLocale( 7627): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7463:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7376/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2581): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7463/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2581): bindWebServices(): registering our AIDL callback...
V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3b3a710c
,I/SundryService( 2581): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2581): ServiceHandler.handleMessage: mWaitCount=0
,I/GCoreNlp( 1759): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  882): Explicit concurrent mark sweep GC freed 16194(849KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.931ms total 136.580ms
,D/GetNotificationsWS( 2581): onServiceConnected()
,D/GetNotificationsWS( 2581): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2581): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2581): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2581): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2581): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2581): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,I/Launcher( 1572): Deferring update until onResume
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2581): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2581): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2581): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7663 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2581): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2581): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2581): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2581): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2581): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2581): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2581): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1416): onFinishInput()
,W/IInputConnectionWrapper( 6542): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7663): Register our PhoneStateListener
,V/SetupWizard( 7663): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 7489:com.google.android.talk/u0a70 (adj 15): empty #7
,I/LaunchCheckinHandler(  882): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,217
W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7489/cgroup.procs: No such file or directory
,D/GCM     ( 1759): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1759): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7688 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  882): done {bc22c3a, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [5921ms]
,V/AlarmManager(  882): done {3d1838ff, *walarm*:com.google.android.intent.action.SEND_IDLE} [3347ms]
,D/GCM     ( 1759): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7714 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 22.194ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.495ms
,I/ActivityManager(  882): Killing 7523:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.779ms
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7523/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7736 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7753 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7588:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  882): Killing 7607:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7588/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7607/cgroup.procs: No such file or directory
,W/ResourcesManager( 7753): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7753): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7753): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7753): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7753): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7753): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7753): MmsConfig.loadFromResources
,E/Babel_SMS( 7753): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7753): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7753): startup - clean
,I/Babel   ( 7753): deleted: false for 0
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7786 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7753): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7753): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7753): Unsupported mime video/mpeg2
,W/asset   ( 7786): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7786): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7786): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7786): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7753): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7753): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7753): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7753): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7753): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 1954): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1954): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1954): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1652a2cb new=com.google.android.velvet.VelvetApplication@1652a2cb
,I/UpdateIcingCorporaServi( 7714): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7818 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7753): onServiceConnected
W/Babel   ( 7753): Attempted to change video mute state without an active call.
,I/art     ( 1954): Explicit concurrent mark sweep GC freed 47508(2MB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 14MB/24MB, paused 1.167ms total 122.746ms
,W/ResourcesManager( 7753): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7753): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7714): UpdateCorporaTask done [took 208 ms] updated apps [took 208 ms] 
,I/ActivityManager(  882): Killing 7688:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7753): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7753): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7753): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7688/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7848 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7663:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7663/cgroup.procs: No such file or directory
,D/Finsky  ( 7848): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7848): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7848): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7848): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7848): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7848): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7848): Skipping gmscore version check
,I/ActivityManager(  882): Killing 7736:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_7736/cgroup.procs: No such file or directory
,D/Finsky  ( 7848): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7848): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/TaskPersister(  882): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 1954): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/Icing   ( 1954): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 7786:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_7786/cgroup.procs: No such file or directory
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=308, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310867, SEQNUM=4492, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-488, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,E/BackupManagerService(  882): Timeout restoring application @pm@
W/BackupManagerService(  882): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1759): Restore processing aborted, no more packages
,E/BackupManagerService(  882): Failure getting next package name
,E/BackupManagerService(  882): Duplicate finish
,I/ActivityManager(  882): Killing 7714:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_7714/cgroup.procs: No such file or directory
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:34000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=296, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310925, SEQNUM=4496, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-521, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1416): run()
I/Keyboard.Facilitator( 1416): flushDynamicLanguageModels()
,I/ConfigService( 1759): onCreate
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310186, SEQNUM=4500, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-579, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ConfigService( 1759): onDestroy
,I/ClearcutLoggerApiImpl( 1759): disconnect managed GoogleApiClient
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  882): send {1a28d668, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {1a96e4d0, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  882): send {14d6fcc9, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  882): send {1c25c1d7, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  882): done {1a96e4d0, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [23ms]
,I/art     (  882): Explicit concurrent mark sweep GC freed 17576(883KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.005ms total 128.529ms
,V/AlarmManager(  882): done {1a28d668, *alarm*:android.intent.action.TIME_TICK} [168ms]
,V/AlarmManager(  882): done {14d6fcc9, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [173ms]
,V/AlarmManager(  882): done {1c25c1d7, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [185ms]
,I/CheckinService( 1954): Checkin interval check for package: unspecified last checkin: 1450745540055 min interval config: 0 actual interval: 76820
,I/EventLogService( 1954): Aggregate from 1450745536539 (log), 1450743724134 (data)
,I/CheckinService( 1954): Checking schedule, now: 1450745616886 next: 1450745570008
I/CheckinService( 1954): active receiver: enabled
,I/CheckinService( 1954): Preparing to send checkin request
,I/EventLogService( 1954): Accumulating logs since 1450745616883
,I/CheckinRequestBuilder( 1954): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1954): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1759): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1759): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7935 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7935): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7935): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7935): VM with version 2.1.0 has multidex support
,I/MultiDex( 7935): install
I/MultiDex( 7935): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7935): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7935): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7935): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@218c152: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7935): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1759): callingUid 10016, callindPid: 1759
,E/MDM     ( 1759): [208] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1759): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1954): Restart initialization of location
,V/GLSActivity( 1759): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 7935): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7935): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7935): Install completed successfully. count=14 extracted=0
,I/art     ( 1759): Explicit concurrent mark sweep GC freed 77215(4MB) AllocSpace objects, 25(423KB) LOS objects, 39% free, 15MB/25MB, paused 1.345ms total 137.754ms
,E/DataBuffer( 1759): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8bf8cfd)
,E/DataBuffer( 1759): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f324df2)
E/DataBuffer( 1759): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17571c43)
,E/DataBuffer( 1759): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1985a2c0)
,E/DataBuffer( 1759): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@35fcfbf9)
,W/GCoreFlp( 1759): No location to return for getLastLocation()
W/FusedLocationProvider( 1759): location=null
,D/WVCdm   (  300): Instantiating CDM.
,I/WVCdm   (  300): CdmEngine::OpenSession
,I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee3000
,E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee3000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xb561e960
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb8cf4be0, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8cdd2c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e2a7c0, idLength=0xbede02b0
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  300): PrepareKeyRequest: nonce=352933624
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8cdc428
D/DrmWidevineDash(  300): message_length=1591, signature=0xb8cdc1d8, signature_length=3202220692
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7974): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7974): dex2oat took 83.425ms (threads: 4)
,I/Adreno-EGL( 7935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7935): Local Branch: 
I/Adreno-EGL( 7935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7935): Local Patches: NONE
I/Adreno-EGL( 7935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7935): Local Branch: 
I/Adreno-EGL( 7935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7935): Local Patches: NONE
I/Adreno-EGL( 7935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  300): CdmEngine::OpenSession
I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee3000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee3000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  300): hlos api version =  9
,D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xb1459960
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb8d64050, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8cdd2e0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e2a7e0, idLength=0xbede02b0
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=3711417598
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8ce3a80
D/DrmWidevineDash(  300): message_length=1626, signature=0xb8ce40e0, signature_length=3202220692
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7935): Local Branch: 
I/Adreno-EGL( 7935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7935): Local Patches: NONE
I/Adreno-EGL( 7935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7935): Local Branch: 
I/Adreno-EGL( 7935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7935): Local Patches: NONE
I/Adreno-EGL( 7935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1954): Classify the device as Phone.
,I/CheckinTask( 1954): Sending checkin request (9510 bytes)
,I/CheckinRequestBuilder( 1954): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1954): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1954): Classify the device as Phone.
,I/CheckinTask( 1954): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1954): Checking schedule, now: 1450745619676 next: 1451346756670
I/CheckinService( 1954): active receiver: disabled
,D/CheckinService( 1954): Recording last checkin time for package unspecified as 1450745619687
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8004 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8004): Register our PhoneStateListener
,V/SetupWizard( 8004): Connected to Gservices successfully
,D/GCM     ( 1759): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Killing 7818:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  882): Killing 7627:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7818/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7627/cgroup.procs: No such file or directory
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8026 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@4db49dd
,I/GCoreNlp( 1759): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8063 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8085 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7848:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_7848/cgroup.procs: No such file or directory
,W/ResourcesManager( 7753): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7753): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8085): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8108 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8004:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.390ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.255ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.467ms
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_8004/cgroup.procs: No such file or directory
,W/asset   ( 8108): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8108): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8108): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8108): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  882): Explicit concurrent mark sweep GC freed 18264(1020KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.408ms total 112.442ms
,D/PackageBroadcastService( 1954): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1954): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1652a2cb new=com.google.android.velvet.VelvetApplication@1652a2cb
,I/UpdateIcingCorporaServi( 8026): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1954): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8135 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8135): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8026): UpdateCorporaTask done [took 143 ms] updated apps [took 143 ms] 
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8159 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7935:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_7935/cgroup.procs: No such file or directory
,D/Finsky  ( 8159): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8159): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8159): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8159): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8159): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8159): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8159): Skipping gmscore version check
,I/ActivityManager(  882): Killing 8063:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_8063/cgroup.procs: No such file or directory
,D/Finsky  ( 8159): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8159): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1954): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1954): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 8108:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_8108/cgroup.procs: No such file or directory
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  882): Killing 7753:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7753/cgroup.procs: No such file or directory
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6542): Connected to the server!
I/jxcore-log( 6542): 
,I/chromium( 6542): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310393, SEQNUM=4518, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-720, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  882): send {1a28d668, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {83b4e5, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {83b4e5, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,V/AlarmManager(  882): done {1a28d668, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  882): send {83b4e5, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {83b4e5, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6542): --- start :testFindPeers.js---
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): testFindPeers created [object Object]
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): serverPort is 8876
I/jxcore-log( 6542): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT3784
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): bind: Binding a new listener
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6542): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6542): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): start: OK
I/io.jxcore.node.ConnectionHelper( 6542): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT3784
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6542): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6542): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6542): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7511a7cc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7511a7cc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service
,D/WifiP2pService(  882): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): start: Starting P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6542): start: OK
,I/jxcore-log( 6542): StartBroadcasting started ok
I/jxcore-log( 6542): 
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,I/chromium( 6542): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6542): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6542): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6542): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-29
I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 6542): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service request added successfully
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 1 c0
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service discovery started successfully
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792] is available
I/jxcore-log( 6542): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT3792","peerAvailable":true}]
I/jxcore-log( 6542): 
I/jxcore-log( 6542): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 6542): 
I/jxcore-log( 6542): weAreDoneNow
I/jxcore-log( 6542): 
I/jxcore-log( 6542): done, now sending data to server
I/jxcore-log( 6542): 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 02
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 02
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): P2P-FIND-STOPPED 
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  298): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-51
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -51 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6542): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service request added successfully
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service discovery started successfully
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-29
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] is available
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792] already in the list, will not add again
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 a2
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 2 
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1437): P2P-FIND-STOPPED 
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  298): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
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
,D/WifiP2pService(  882): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 3 c0
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
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
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6542): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service request added successfully
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 7e
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139310 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139310 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service discovery started successfully
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8784","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8784] is available
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086] is available
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT3792","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3792] already in the list, will not add again
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 0a
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 3 
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1437): P2P-FIND-STOPPED 
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  298): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
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
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=-2ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6542): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service request added successfully
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
I/wpa_supplicant( 1437): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service discovery started successfully
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 7e
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8123","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] already in the list, will not add again
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] is available
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375] is available
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] is available
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT884","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT884] is available
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1382","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT1382] is available
,I/jxcore-log( 6542): teardown
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): testFindPeers stopped
I/jxcore-log( 6542): 
,I/io.jxcore.node.ConnectionHelper( 6542): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): stop: Stopping services
,D/WifiP2pService(  882): InactiveState{ when=0 what=139298 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139298 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): stop: Stopping P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): P2P-FIND-STOPPED 
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  298): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
,D/WifiP2pService(  882): InactiveState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
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
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: NOT_INITIALIZED
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
D/WifiP2pService(  882): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6542): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setState: NOT_STARTED
,I/jxcore-log( 6542): StopBroadcasting went ok
I/jxcore-log( 6542): 
,I/chromium( 6542): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6542): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6542): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6542): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 6542): --- start :testSendData.js---
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): daya100000
I/jxcore-log( 6542): 
I/jxcore-log( 6542): check server
I/jxcore-log( 6542): 
I/jxcore-log( 6542): serverPort is 34495
I/jxcore-log( 6542): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT3784
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): bind: Binding a new listener
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6542): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6542): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): start: OK
I/io.jxcore.node.ConnectionHelper( 6542): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT3784
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6542): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6542): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6542): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3784","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7511a7cc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7511a7cc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service
D/WifiP2pService(  882): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): start: OK
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6542): start: OK
,I/jxcore-log( 6542): StartBroadcasting started ok
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): null
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:58:46.030Z SendDataTCPServer.js: TCP/IP server is bound to port: 34495
I/jxcore-log( 6542): 
,I/chromium( 6542): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6542): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6542): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 6542): onDiscoveryManagerStateChanged: RUNNING
D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): P2P-FIND-STOPPED 
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  298): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: RESTARTING
D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 4 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 5 c0
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-57
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=8 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 6542): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service request added successfully
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service discovery started successfully
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] already in the list, will not add again
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 92
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 5 
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): P2P-FIND-STOPPED 
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  298): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139265 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 6 c0
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 92
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=18 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=18 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6542): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service request added successfully
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service discovery started successfully
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-57
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] already in the list, will not add again
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375] already in the list, will not add again
,W/bt-btif ( 2463): info:x10
,D/        ( 2463): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2463): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2463): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 2463): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2463): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2463): Entering PendingCommandState State
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44c18a4:true
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=8235 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2463): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2463): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2463): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
D/BluetoothAdapterService( 2463): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27c8289
,D/BluetoothMetrics( 2463): btclass5a020c
,D/Checkin ( 2463): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 2463): StableState(): Entering Off State
,W/ResourcesManager( 8235): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/bt-btif ( 2463): new conn_srvc id:26, app_id:255
W/bt-btif ( 2463): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2463): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Incoming connection initialized (thread ID: 796)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6542): Entering thread (ID: 796)
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dacd9c2:true
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): onBytesRead: Read 83 bytes successfully (thread ID: 796)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): onBytesWritten: 81 bytes successfully written (thread ID: 796)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): removeThreadFromList: Removing thread with ID 796
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Handshake thread disposed (thread ID: 796)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6542): Exiting thread (ID: 796)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/io.jxcore.node.ConnectionHelper( 6542): onConnected: Incoming connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/io.jxcore.node.ConnectionHelper( 6542): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6542): onConnected: Incoming socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], created successfully
D/io.jxcore.node.ConnectionHelper( 6542): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6542): Entering thread (ID: 797)
,I/jxcore-log( 6542): 2015-12-22T00:59:34.225Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6542): 
I/io.jxcore.node.IncomingSocketThread( 6542): Local host address: localhost/127.0.0.1, port: 34495
,D/io.jxcore.node.IncomingSocketThread( 6542): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6542): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6542): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6542): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6542): Exiting thread (ID: 797)
,D/io.jxcore.node.StreamCopyingThread( 6542): Entering thread (ID: 798, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6542): Entering thread (ID: 799, name: Receiver)
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  882): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8278 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8026:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_8026/cgroup.procs: No such file or directory
,W/ResourcesManager( 8278): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5de9609:true
,I/ActivityManager(  882): Killing 8085:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_8085/cgroup.procs: No such file or directory
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/jxcore-log( 6542): 2015-12-22T00:59:34.984Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:34.990Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:34.994Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:34.998Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.003Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.009Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.048Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.056Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.088Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.094Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.128Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.136Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.168Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.176Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.207Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.215Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:35.248Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6542): 
,W/bt-btif ( 2463): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 6542): Either failed to read from the output stream or write to the input stream (thread ID: 799, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6542): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6542): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 797
D/io.jxcore.node.IncomingSocketThread( 6542): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6542): doStop: Thread ID: 799
D/io.jxcore.node.IncomingSocketThread( 6542): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6542): doStop: Thread ID: 798
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6542): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6542): Exiting thread (ID: 799, name: Receiver)
,W/bt-rfcomm( 2463): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 2463): RFCOMM_DisconnectInd LCID:0x41
W/io.jxcore.node.StreamCopyingThread( 6542): Either failed to read from the output stream or write to the input stream (thread ID: 798, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6542): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6542): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6542): Exiting thread (ID: 798, name: Sender)
I/jxcore-log( 6542): 2015-12-22T00:59:35.295Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6542): 
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 02
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 02
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 a2
,E/bt-btm  ( 2463): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2463): onReceive
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8309 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8d189c5:true
,I/BTConnectionReceiver( 8309): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,D/btif_config_util( 2463): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8347 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 8309): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/ActivityManager(  882): Killing 8135:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_8135/cgroup.procs: No such file or directory
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 92
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{261b0a2f u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2463): info:x10
,D/        ( 2463): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2463): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2463): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 2463): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2463): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2463): Entering PendingCommandState State
,I/ActivityManager(  882): Killing 1954:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  882): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2738f2d4)
,D/WifiService(  882): Client connection lost with reason: 4
,D/ConnectivityService(  882): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  882): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 92
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_1954/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2463): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2463): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2463): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2463): StableState(): Entering Off State
,D/BluetoothMetrics( 2463): btclass5a020c
,D/Checkin ( 2463): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2463): new conn_srvc id:26, app_id:255
W/bt-btif ( 2463): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2463): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Incoming connection initialized (thread ID: 800)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6542): Entering thread (ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): onBytesRead: Read 77 bytes successfully (thread ID: 800)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): onBytesWritten: 81 bytes successfully written (thread ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): removeThreadFromList: Removing thread with ID 800
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Handshake thread disposed (thread ID: 800)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
,I/io.jxcore.node.ConnectionHelper( 6542): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
D/io.jxcore.node.ConnectionHelper( 6542): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6542): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], created successfully
,D/io.jxcore.node.ConnectionHelper( 6542): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6542): Exiting thread (ID: 800)
,D/io.jxcore.node.IncomingSocketThread( 6542): Entering thread (ID: 801)
,I/io.jxcore.node.IncomingSocketThread( 6542): Local host address: localhost/127.0.0.1, port: 34495
D/io.jxcore.node.IncomingSocketThread( 6542): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6542): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6542): 2015-12-22T00:59:58.565Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6542): 
,I/io.jxcore.node.StreamCopyingThread( 6542): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6542): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6542): Exiting thread (ID: 801)
,D/io.jxcore.node.StreamCopyingThread( 6542): Entering thread (ID: 802, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6542): Entering thread (ID: 803, name: Receiver)
,I/jxcore-log( 6542): 2015-12-22T00:59:59.597Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.631Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.635Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.640Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.646Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.653Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.687Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.693Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.728Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.737Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.745Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.783Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.797Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.803Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.809Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.816Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.848Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.886Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.918Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.940Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.946Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.952Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.988Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T00:59:59.993Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:00.032Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:00.068Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:00.108Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:00.115Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:00.121Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:00.158Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6542): 
,W/bt-btif ( 2463): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 6542): Either failed to read from the output stream or write to the input stream (thread ID: 803, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6542): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6542): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 801
D/io.jxcore.node.IncomingSocketThread( 6542): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6542): doStop: Thread ID: 803
,D/io.jxcore.node.IncomingSocketThread( 6542): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6542): doStop: Thread ID: 802
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6542): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,W/io.jxcore.node.StreamCopyingThread( 6542): Either failed to read from the output stream or write to the input stream (thread ID: 802, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6542): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6542): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6542): Exiting thread (ID: 802, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6542): Exiting thread (ID: 803, name: Receiver)
,I/jxcore-log( 6542): 2015-12-22T01:00:00.208Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6542): 
,W/bt-rfcomm( 2463): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2463): RFCOMM_DisconnectInd LCID:0x43
,D/btif_config_util( 2463): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2463): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2463): onReceive
,I/BTConnectionReceiver( 8309): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8309): Bluetooth Device Name: G3-1
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1437): P2P-FIND-STOPPED 
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  298): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
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
,D/WifiP2pService(  882): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-42
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6542): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service request added successfully
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1437): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  298): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service discovery started successfully
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4323","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323] already in the list, will not add again
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] already in the list, will not add again
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-42
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-57
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-4ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -57 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4323]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT375","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375] already in the list, will not add again
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 7 
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1437): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 8 c0
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  298): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
,D/TCMD    (  475): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT375]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/io.jxcore.node.ConnectionHelper( 6542): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6542): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] is available
,I/jxcore-log( 6542): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT1510","peerAvailable":true}]
I/jxcore-log( 6542): 
I/jxcore-log( 6542): Found peer : LGE-Nexus 5_PT1510, Available: true
I/jxcore-log( 6542): 
I/jxcore-log( 6542): startWithNextDevice
I/jxcore-log( 6542): 
I/jxcore-log( 6542): device[1]: 34:FC:EF:11:AE:67
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:18.393Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6542): 
I/jxcore-log( 6542): 2015-12-22T01:00:18.394Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6542): 
I/jxcore-log( 6542): 2015-12-22T01:00:18.394Z SendDataConnector.js: do connect now
I/jxcore-log( 6542): 
I/io.jxcore.node.ConnectionHelper( 6542): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 6542): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): connect: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6542): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 804)
W/BluetoothAdapter( 6542): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2463): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2463): info:x10
,D/        ( 2463): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2463): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2463): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2463): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 2463): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2463): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2463): Entering PendingCommandState State
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2463): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2463): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 2463): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2463): StableState(): Entering Off State
,D/BluetoothMetrics( 2463): btclass5a020c
,D/Checkin ( 2463): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2463): new conn_srvc id:26, app_id:1
W/bt-btif ( 2463): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2463): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): onSocketConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 804)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): onBytesWritten: 81 bytes successfully written (thread ID: 805)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): Outgoing connection initialized (*handshake* thread ID: 805)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): Exiting thread (thread ID: 804)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6542): Entering thread (ID: 805)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): onBytesRead: Read 77 bytes successfully (thread ID: 805)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6542): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): onHandshakeSucceeded: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,I/io.jxcore.node.ConnectionHelper( 6542): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,D/io.jxcore.node.ConnectionHelper( 6542): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6542): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6542): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6542): Exiting thread (ID: 805)
,D/io.jxcore.node.OutgoingSocketThread( 6542): Entering thread (ID: 806)
,D/io.jxcore.node.OutgoingSocketThread( 6542): Server socket local port: 53870
I/io.jxcore.node.OutgoingSocketThread( 6542): Now accepting connections...
,W/bt-btif ( 2463): new conn_srvc id:26, app_id:255
W/bt-btif ( 2463): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2463): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2463): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Incoming connection initialized (thread ID: 807)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6542): Entering thread (ID: 807)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): onBytesRead: Read 77 bytes successfully (thread ID: 807)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Got valid identity from [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): onBytesWritten: 81 bytes successfully written (thread ID: 807)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): removeThreadFromList: Removing thread with ID 807
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Handshake thread disposed (thread ID: 807)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
I/io.jxcore.node.ConnectionHelper( 6542): onConnected: Incoming connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510]
D/io.jxcore.node.ConnectionHelper( 6542): hasConnection: We have an outgoing connection with peer with ID 34:FC:EF:11:AE:67
,W/io.jxcore.node.ConnectionHelper( 6542): onConnected: Already connected with peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6542): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6542): onConnected: Incoming socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510], created successfully
,D/io.jxcore.node.ConnectionHelper( 6542): onConnected: The total number of connections is now 2
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6542): Exiting thread (ID: 807)
,D/io.jxcore.node.IncomingSocketThread( 6542): Entering thread (ID: 808)
,I/io.jxcore.node.IncomingSocketThread( 6542): Local host address: localhost/127.0.0.1, port: 34495
D/io.jxcore.node.IncomingSocketThread( 6542): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6542): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6542): 2015-12-22T01:00:19.535Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6542): 
,I/io.jxcore.node.StreamCopyingThread( 6542): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6542): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6542): Exiting thread (ID: 808)
,D/io.jxcore.node.StreamCopyingThread( 6542): Entering thread (ID: 809, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6542): Entering thread (ID: 810, name: Receiver)
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/io.jxcore.node.ConnectionHelper( 6542): onListeningForIncomingConnections: Outgoing connection is using port 53870 (peer ID: 34:FC:EF:11:AE:67)
,I/jxcore-log( 6542): 2015-12-22T01:00:19.791Z SendDataConnector.js: CLIENT connected to 53870, error: null
I/jxcore-log( 6542): 
I/jxcore-log( 6542): 2015-12-22T01:00:19.792Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6542): 
,I/io.jxcore.node.IncomingSocketThread( 6542): Incoming data from address: /127.0.0.1, port: 53870
,D/io.jxcore.node.IncomingSocketThread( 6542): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6542): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6542): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6542): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6542): Exiting thread (ID: 806)
,D/io.jxcore.node.StreamCopyingThread( 6542): Entering thread (ID: 812, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6542): Entering thread (ID: 811, name: Sender)
,I/jxcore-log( 6542): 2015-12-22T01:00:19.818Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6542): 
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.353Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.356Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.362Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.397Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6542): 
,D/        ( 2463): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6542): 2015-12-22T01:00:20.407Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.423Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.430Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6542): 
,D/        ( 2463): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15796
,I/jxcore-log( 6542): 2015-12-22T01:00:20.460Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.469Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.499Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.505Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.538Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6542): 
,D/        ( 2463): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 6542): 2015-12-22T01:00:20.547Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.575Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6542): 
,D/        ( 2463): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1936
,I/jxcore-log( 6542): 2015-12-22T01:00:20.606Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6542): 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
I/jxcore-log( 6542): 2015-12-22T01:00:20.609Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.663Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.695Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.698Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.710Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.748Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.754Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.772Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.788Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.816Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.849Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.857Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.862Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.863Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6542): 
I/jxcore-log( 6542): oneRoundDownNow
I/jxcore-log( 6542): 
I/jxcore-log( 6542): 2015-12-22T01:00:20.865Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.866Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6542): 
D/io.jxcore.node.ConnectionHelper( 6542): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
,I/io.jxcore.node.IncomingSocketThread( 6542): close
D/io.jxcore.node.IncomingSocketThread( 6542): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6542): doStop: Thread ID: 812
D/io.jxcore.node.IncomingSocketThread( 6542): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6542): doStop: Thread ID: 811
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 6542): Either failed to read from the output stream or write to the input stream (thread ID: 811, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6542): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6542): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 6542): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 6542): Either failed to read from the output stream or write to the input stream (thread ID: 812, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6542): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6542): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1,
D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6542): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
E/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67,
,D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
D/io.jxcore.node.StreamCopyingThread( 6542): Exiting thread (ID: 811, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6542): Exiting thread (ID: 812, name: Receiver)
I/jxcore-log( 6542): 2015-12-22T01:00:20.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): ---- round done--------
I/jxcore-log( 6542): 
I/jxcore-log( 6542): startWithNextDevice
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:20.882Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6542): 
,W/bt-btif ( 2463): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 6542): 2015-12-22T01:00:20.898Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6542): 
,W/bt-btif ( 2463): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 6542): Either failed to read from the output stream or write to the input stream (thread ID: 810, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6542): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6542): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 808
D/io.jxcore.node.IncomingSocketThread( 6542): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6542): doStop: Thread ID: 810
D/io.jxcore.node.IncomingSocketThread( 6542): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6542): doStop: Thread ID: 809
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6542): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6542): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6542): Exiting thread (ID: 810, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 6542): Either failed to read from the output stream or write to the input stream (thread ID: 809, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6542): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6542): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT1510] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 6542): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6542): Exiting thread (ID: 809, name: Sender)
,I/jxcore-log( 6542): 2015-12-22T01:00:20.936Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6542): 
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 92
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 52
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 52
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 0a
,E/bt-btm  ( 2463): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2463): onReceive
,I/BTConnectionReceiver( 8309): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8309): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 2463): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6542): timeout now
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 6542): 
I/jxcore-log( 6542): sendReportNow
I/jxcore-log( 6542): 
I/jxcore-log( 6542): done, now sending data to server
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:26.041Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6542): 
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 8 
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 c0
,D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 9 c0
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/wpa_supplicant( 1437): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
,D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 92
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 9 
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{3a9c6840 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  298): Event received = P2P-SERV-DISC-REQ 2412 ee
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6542): teardown
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): testSendData stopped
I/jxcore-log( 6542): 
,I/io.jxcore.node.ConnectionHelper( 6542): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6542): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6542): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6542): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6542): stop: Stopping services
,D/WifiP2pService(  882): InactiveState{ when=0 what=139298 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139298 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): stop: Stopping P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1437): P2P-FIND-STOPPED 
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  298): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1437): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  298): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
,D/MDMCTBK (  298): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): setState: NOT_INITIALIZED
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
D/WifiP2pService(  882): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6542): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6542): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6542): setState: NOT_STARTED
,I/jxcore-log( 6542): StopBroadcasting went ok
I/jxcore-log( 6542): 
,I/jxcore-log( 6542): 2015-12-22T01:00:45.898Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6542): 
,I/chromium( 6542): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6542): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6542): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6542): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6542): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6542): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 6542): ****TEST TOOK:  ms ****
I/jxcore-log( 6542): 
I/jxcore-log( 6542): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6542): 
,D/AndroidRuntime( 8419): 
D/AndroidRuntime( 8419): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8419): CheckJNI is OFF
,D/AndroidRuntime( 8419): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10402 user=-1: uninstall pkg
,I/ActivityManager(  882): Killing 6542:com.test.thalitest/u0a402 (adj 9): stop com.test.thalitest
,W/PackageSettings(  882): Skipping PackageSetting{10286186 com.example.hello/10377} due to missing metadata
,I/WindowState(  882): WIN DEATH: Window{daed547 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  882): Client connection lost with reason: 4
,I/ActivityManager(  882):   Force finishing activity ActivityRecord{3747a280 u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  882): Spurious death for ProcessRecord{3ddc1379 6542:com.test.thalitest/u0a402}, curProc for 6542: null
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10402 user=0: pkg removed
,I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1759): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8440 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     ( 1572): Explicit concurrent mark sweep GC freed 5142(316KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 526us total 91.704ms
,I/Decoder ( 1416): createOrResetDecoder
,I/art     ( 3029): Explicit concurrent mark sweep GC freed 12302(2MB) AllocSpace objects, 18(288KB) LOS objects, 39% free, 7MB/12MB, paused 1.166ms total 115.185ms
,I/ConfigService( 1759): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
,I/art     (  882): Explicit concurrent mark sweep GC freed 39173(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.710ms total 199.994ms
,I/art     (  882): WaitForGcToComplete blocked for 203.980ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 8440): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8472 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 8440): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  882): removeObsoleteFile: deleting file=3_task.xml
,I/Launcher( 1572): Deferring update until onResume
W/asset   ( 8472): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8472): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8472): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8472): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  882): Explicit concurrent mark sweep GC freed 8839(500KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.924ms total 233.192ms
,I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8490 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8159:com.android.vending/u0a32 (adj 15): empty #7
,D/AndroidRuntime( 8419): Shutting down VM
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_8159/cgroup.procs: No such file or directory
,W/ContextImpl( 8490): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  882): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=8514 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6433:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_6433/cgroup.procs: No such file or directory
,W/ResourcesManager( 8514): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8514): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8514): VM with version 2.1.0 has multidex support
I/MultiDex( 8514): install
I/MultiDex( 8514): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  882): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=8538 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 23.005ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.735ms
,I/GservicesProvider( 8538): Gservices pushing to system: true; secure/global: true
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 469us total 21.360ms
,I/qdhwcomposer(  282): handle_blank_event: dpy:0 panel power state: 0
,E/SQLiteDatabase( 8538): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 8538): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 8538): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 8538): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8538): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8538): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 8538): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 8538): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/SQLiteDatabase( 8538): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/SQLiteDatabase( 8538): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/SQLiteDatabase( 8538): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/SQLiteDatabase( 8538): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/SQLiteDatabase( 8538): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 8538): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/SQLiteDatabase( 8538): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8538): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8538): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/SQLiteDatabase( 8538): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8538): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8538): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/SQLiteDatabase( 8538): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,D/AndroidRuntime( 8538): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8538): FATAL EXCEPTION: main
E/AndroidRuntime( 8538): Process: com.google.process.gapps, PID: 8538
E/AndroidRuntime( 8538): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8538): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5054)
E/AndroidRuntime( 8538): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/AndroidRuntime( 8538): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/AndroidRuntime( 8538): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 8538): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/AndroidRuntime( 8538): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8538): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8538): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 8538): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8538): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8538): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 8538): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 8538): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 8538): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 8538): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8538): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8538): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 8538): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 8538): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/AndroidRuntime( 8538): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/AndroidRuntime( 8538): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/AndroidRuntime( 8538): 	... 11 more

```
