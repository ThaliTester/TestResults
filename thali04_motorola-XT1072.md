#### Test 549702618c0ebdb_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,D/AndroidRuntime( 6340): 
D/AndroidRuntime( 6340): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6340): CheckJNI is OFF
D/AndroidRuntime( 6340): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6359 uid=10422 gids={50422, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6340): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6359): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6359): Time to load native libraries: 4 ms (timestamps 7792-7796)
I/LibraryLoader( 6359): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6359): Binding Chromium to main looper Looper (main, tid 1) {392444a2}
I/LibraryLoader( 6359): Expected native library version number "",actual native library version number ""
I/chromium( 6359): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6359): Initializing chromium process, singleProcess=true
W/art     ( 6359): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6359): ApplicationContext is null in ApplicationStatus
W/chromium( 6359): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6359): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6359): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6359): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6359): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6359): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6359): Local Branch: 
I/Adreno-EGL( 6359): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6359): Local Patches: NONE
I/Adreno-EGL( 6359): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a9cb4bb:true
W/ActivityManager(  881): Activity pause timeout for ActivityRecord{1e3ad954 u0 com.test.thalitest/.MainActivity t3}
W/art     ( 6359): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6359): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6359): CordovaWebView is running on device made by: motorola
W/art     ( 6359): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6359): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6359): Render dirty regions requested: true
D/Atlas   ( 6359): Validating map...
W/chromium( 6359): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6359): Initialized EGL, version 1.4
D/OpenGLRenderer( 6359): Enabling debug mode 0
I/Keyboard.Facilitator( 1414): onFinishInput()
I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1048
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +977ms (total +1s48ms)
W/IInputConnectionWrapper( 6359): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6359): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6359): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6359): Cannot call determinedVisibility() - never saw a connection for the pid: 6359
,D/JsMessageQueue( 6359): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6359): JniHelper::setJavaVM(0xb7c94310), pthread_self() = -1207810456
D/JX-Cordova( 6359): jxcore cordova android initializing
,W/jxcore-log( 6359): Initializing JXcore engine
W/jxcore-log( 6359): JXcore engine is ready
,W/jxcore-log( 6359): Starting JXcore engine
,W/.test.thalitest( 6359): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10422 path="socket:[8407]" dev="sockfs" ino=8407 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6359): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10422 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6359): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10422 path="socket:[7633]" dev="sockfs" ino=7633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6359): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10422 path="socket:[25577]" dev="sockfs" ino=25577 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6359): Platform android
W/jxcore-log( 6359): 
,W/jxcore-log( 6359): Process ARCH arm
W/jxcore-log( 6359): 
,I/jxcore-log( 6359): JXcore Cordova bridge is ready!
I/jxcore-log( 6359): 
,W/jxcore-log( 6359): JXcore engine is started
I/chromium( 6359): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6359): Toggling radios to true
I/jxcore-log( 6359): 
,D/BluetoothAdapter( 6359): enable(): BT is already enabled..!
,D/WifiService(  881): New client listening to asynchronous messages
,D/WifiService(  881): setWifiEnabled: true pid=6359, uid=10422
,E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6359): Radios toggled
I/jxcore-log( 6359): 
,I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  297):  STA Disconnected !!
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  454): NL - Read 1004 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 1004 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 68 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 68 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  297): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  297): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
E/MDMCTBK (  297): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  297): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  297): Event received = CTRL-EVENT-REGDOM-CHANGE
D/Tethering(  881): InitialState.processMessage what=4
E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881):  0
,D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  295): Clearing all IP addresses on wlan0
,D/TCMD    (  454): NL - Read 60 bytes from update socket.
D/TCMD    (  454): NL - ignore NL message, type = 21
,D/TCMD    (  454): Listening for incoming client connection request
,V/NativeCrypto( 1738): Read error: ssl=0xb7fab0c0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1738): SSL shutdown failed: ssl=0xb7fab0c0: I/O error during system call, Broken pipe
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiMetrics(  881): connected time updated 122355
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6422 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524292
D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=null
,E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  881): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  881): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  295): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6422): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6448 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  881): Explicit concurrent mark sweep GC freed 48929(2MB) AllocSpace objects, 3(232KB) LOS objects, 33% free, 20MB/30MB, paused 2.499ms total 192.114ms
,I/ActivityManager(  881): Killing 6132:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/TCMD    (  454): NL - Read 56 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  297): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1435): wlan0: Trying to associate with SSID 'NG700'
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  297): Event received = Trying to associate with
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1435): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  881): [1,452,267,206,474 ms] noteScanEnd no scan source
D/WifiMonitor(  881): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1f757e36 sup_state=SCANNING debouncing=false
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_6132/cgroup.procs: No such file or directory
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6448): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1738): Scheduling Phenotype for one-off execution 8466 seconds from now (1452267206570)
,D/GetConfigurationSnapshotOperation( 1738): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/TCMD    (  454): NL - Read 312 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 192 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 68 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 1004 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
,I/wpa_supplicant( 1435): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  297): Event received = Associated with c0:ff:d4
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
,D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
D/TCMD    (  454): NL - Read 80 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 80 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/TCMD    (  454): NL - Read 68 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1435): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  297): Event received = WPA: Key negotiation com
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  297): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  297):  STA Connected !!
D/TCMD    (  454): NL - Read 1004 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
,E/MDMCTBK (  297): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  297): get_freq !!, resp=2412
I/MDMCTBK (  297): get_freq !!, Strip data
I/MDMCTBK (  297): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  297): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  297): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  297): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1200337512
I/MDMCTBK (  297): return from set_get_from_wpa_supplicant
I/MDMCTBK (  297): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
E/MDMCTBK (  297): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  297): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  297): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  297): , reply_len: 3, ret: 0
E/MDMCTBK (  297): MdmCutbackHndler, resp=OK
E/MDMCTBK (  297): 
D/MDMCTBK (  297): wifi_set_tx_pwr: Exit
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  881): Network connection established
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
V/AlarmManager(  881): send {2253f031, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  881): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  881): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  881): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  881): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  881): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  295): Setting iface cfg
E/WifiStateMachine(  881): Start Dhcp Watchdog 2
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend false
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  881): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1f9cda56 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1f9cda56 target=com.android.internal.util.StateMachine$SmHandler }
,I/PhenotypeFlagCommitter( 1738): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1738): Using platform SSLCertificateSocketFactory
,I/Babel_SMS( 6448): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6448): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6448): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6448): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6448): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6448): MmsConfig.loadFromResources
,E/Babel_SMS( 6448): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6448): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6448): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/DHCPCD  ( 6493): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6493): version 5.5.6 starting
,E/DHCPCD  ( 6493): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6493): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6493): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/Babel_Crash( 6448): startup - clean
,I/Babel   ( 6448): deleted: false for 0
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/DHCPCD  ( 6493): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6493): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6493): wlan0: sending REQUEST (xid 0x74b6359d), next in 4.00 seconds
,V/AlarmManager(  881): done {2253f031, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [426ms]
,W/VideoCapabilities( 6448): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6448): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6448): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6448): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6448): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6448): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6448): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6448): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6448): onServiceConnected
W/Babel   ( 6448): Attempted to change video mute state without an active call.
,I/ActivityManager(  881): Killing 6173:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6173/cgroup.procs: No such file or directory
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1738): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/DHCPCD  ( 6493): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6493): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6493): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6493): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6493): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6493): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  454): NL - Read 60 bytes from update socket.
D/TCMD    (  454): NL - ignore NL message, type = 20
D/TCMD    (  454): Listening for incoming client connection request
,D/DHCPCD  ( 6493): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/global frequency( 2587): no tags to log
D/Checkin ( 2587): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2587): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): WifiStateMachine DHCP successful
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  881): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/art     ( 2587): Explicit concurrent mark sweep GC freed 14877(802KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.100ms total 71.102ms
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  881): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService(  881): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  881): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  881): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  881): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  881): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881):    accepting network in place of null
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  881): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  881): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/BSUtils ( 2587): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2587): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2587): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 15:33:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452267208696], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452267208677]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
,D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1521): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1521): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     ( 1475): Explicit concurrent mark sweep GC freed 56472(3MB) AllocSpace objects, 36(1255KB) LOS objects, 40% free, 7MB/12MB, paused 670us total 48.287ms
,D/BSUtils ( 2587): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2587): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2587): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  881): Explicit concurrent mark sweep GC freed 31134(1571KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.925ms total 124.654ms
,D/BSUtils ( 2587): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2587): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2587): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2587): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2587): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2587): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2587): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2587): publish the event [tag = DEV_ATTRIBS event name = SW]
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524295
,I/global frequency( 2587): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2587): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2587): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  881): MasterInitialState.processMessage what=3
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6565 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1475): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2587): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2587): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2587): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2587): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2587): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2587): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2587): [debug] > CusSM.onRadioDown
,D/CCE     ( 2587): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2587): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2587): Registering with Alarm Manager to restart CCE
,I/MusicStore( 6565): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6565): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6565): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6565): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,V/AlarmManager(  881): send {e5639d, *walarm*:com.google.android.intent.action.SEND_IDLE}
,W/ResourcesManager( 6565): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6565): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6565): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6565): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6565): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3644045e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6565): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6565): GMSCore installation verified
,I/ConfigStore( 6565): Config Database version: 1
,I/MediaRouter( 6565): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6565): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6565): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  881): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/NetworkMonitor( 6565): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6594 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6565): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6565): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 5966:android.process.acore/u0a7 (adj 15): empty #7
,V/Mms     ( 6594): mnc/mcc: 
V/Mms     ( 6594): tag: int value: recipientLimit - 20
V/Mms     ( 6594): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6594): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6594): tag: int value: maxSubjectLength - 80
V/Mms     ( 6594): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6594): tag: bool value: enableGroupMms - false
V/Mms     ( 6594):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_5966/cgroup.procs: No such file or directory
,W/ResourcesManager( 6594): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6621 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.271ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.200ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.938ms
,I/ActivityManager(  881): Killing 6043:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6621): Register our PhoneStateListener
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_6043/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6621): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6621): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6448:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6448/cgroup.procs: No such file or directory
,I/CheckinService( 6236): Checkin interval check for package: unspecified last checkin: 1452267128220 min interval config: 0 actual interval: 82379
,I/CheckinService( 6236): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6236): SYNC; picasa accounts
,I/CheckinService( 6236): Checking schedule, now: 1452267210636 next: 1452267158199
I/CheckinService( 6236): active receiver: enabled
,D/NetworkLogImpl( 6236): Loaded NetworkSpeedPredictor
,I/CheckinService( 6236): Preparing to send checkin request
I/iu.Environment( 6236): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6236): Accumulating logs since 1452267125178
,I/iu.UploadsManager( 6236): num queued entries: 0
I/iu.UploadsManager( 6236): num updated entries: 0
,I/iu.SyncManager( 6236): NEXT; no task
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6653 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6236): Checkin reason type: 8 attempt count: 1
,D/WifiService(  881): New client listening to asynchronous messages
,E/ActivityThread( 6236): Failed to find provider info for com.google.android.wearable.settings
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6676 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6693 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6676): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6676): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6693): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 6676): VM with version 2.1.0 has multidex support
I/MultiDex( 6676): install
I/MultiDex( 6676): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6676): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6676): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3638e167: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6676): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6676): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6676): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 6693): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6693): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6693): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6693): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6693): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6693): MmsConfig.loadFromResources
,E/Babel_SMS( 6693): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6693): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2587): now: 197867 ,futureTime: 9223372036854775807
D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2587): now: 197868 ,futureTime: 9223372036854775807
D/PollingManager( 2587): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2587): now: 197868 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2587): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1475): now: 197874 ,futureTime: 86474598
D/Central_PollingManager( 1475): Polling alarm set to expire at: 86474598 Current Time: 197874
,D/NativeLibraryUtils( 6676): Install completed successfully. count=14 extracted=0
,D/OtaApp  ( 2587): [debug] > PollingManagerService, now: 197889 ,futureTime: 2457835
D/OtaApp  ( 2587): [debug] > Polling alarm set to expire at: 2457835 Current Time: 197890
,D/OtaApp  ( 2587): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2587): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2587): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2587): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2587): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2587): publish the event [tag = MOT_OTA event name = LOG]
,I/NetworkMonitor( 6565): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2587): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2587): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2587): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/WVCdm   (  307): Instantiating CDM.
,I/WVCdm   (  307): CdmEngine::OpenSession
I/WVCdm   (  307): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  307): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  307): Service_Initialize: starts!
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
,D/QSEECOMAPI: (  307): Loaded image: APP id = 3
D/DrmWidevineDash(  307): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  307): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
E/DrmWidevineDash(  307): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  307): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: starts! SID=0xbe9b14e0
D/DrmWidevineDash(  307): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: starts! randomData=0xb71af310, dataLength=8
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb71137a0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  307): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  307): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  307): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  307): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: starts! deviceID=0xb71fb730, idLength=0xb13cf730
W/art     ( 6693): Suspending all threads took: 9.221ms
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  307): PrepareKeyRequest: nonce=1401665202
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb70b4888
,D/DrmWidevineDash(  307): message_length=1591, signature=0xb710da60, signature_length=2973562644
,I/art     (  881): Explicit concurrent mark sweep GC freed 15113(732KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.082ms total 135.463ms
,D/OtaApp  ( 2587): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2587): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2587): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2587): createDeviceIdOrLogin update_device
,D/Checkin ( 2587): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2587): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2587): isDeviceProvisioned: deviceId = 2072049230914535424
D/CCE     ( 2587): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2587): createDeviceIdOrLogin update_device
D/Checkin ( 2587): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2587): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2587): set mOutstandingReq to true.
I/ Nonce  ( 2587):  Nonce getNonce 
I/ Nonce  ( 2587):  Nonce Request 
I/ Nonce  ( 2587):  Nonce execute Request 
,D/MMApiWebService( 2587): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1475): Explicit concurrent mark sweep GC freed 4816(214KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 876us total 58.821ms
,D/MMApiProvisionService( 2587): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2587): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2587): createDeviceIdOrLogin update_device
D/Checkin ( 2587): publish the event [tag = MOT_CCE event name = LOG]
D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature returns 0
D/MMApiProvisionService( 2587): Not proxy app, so login/provision not allowed
I/WVCdm   (  307): CdmEngine::CloseSession
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  307): L3 Terminate.
D/DrmWidevineDash(  307): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  307): Service_Uninitialize: starts!
D/QSEECOMAPI: (  307): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  307): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  307): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_Terminate: ends! returns 0
,W/Settings( 6693): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6693): startup - clean
,I/Babel   ( 6693): deleted: false for 0
,D/MMApiWebService( 2587): generating token using payload instead of using session token
,D/ Nonce  ( 2587):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6734 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MMApiWSBase( 2587): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2587): publish the event [tag = MOT_CCE event name = LOG]
,I/WVCdm   (  307): CdmEngine::OpenSession
I/WVCdm   (  307): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  307): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities( 6693): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  307): Service_Initialize: starts!
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
,W/AudioCapabilities( 6693): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6693): Unsupported mime video/mpeg2
,D/QSEECOMAPI: (  307): Loaded image: APP id = 3
,I/VideoCapabilities( 6693): Unsupported profile 4 for video/mp4v-es
D/DrmWidevineDash(  307): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  307): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
E/DrmWidevineDash(  307): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
,W/VideoCapabilities( 6693): Unrecognized profile 2130706433 for video/avc
D/DrmWidevineDash(  307): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: starts!
W/VideoCapabilities( 6693): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6693): Unrecognized profile 2130706433 for video/avc
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  307): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: starts! SID=0xbe9b14e0
,D/DrmWidevineDash(  307): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: starts! randomData=0xb7135140, dataLength=8
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb70af268, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  307): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  307): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  307): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  307): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: starts! deviceID=0xb71fb770, idLength=0xb54b9730
,W/VideoCapabilities( 6693): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  307): PrepareKeyRequest: nonce=2717655563
D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb70b4888
D/DrmWidevineDash(  307): message_length=1626, signature=0xb709c6b8, signature_length=3041629972
,I/vclib   ( 6693): onServiceConnected
,W/Babel   ( 6693): Attempted to change video mute state without an active call.
,I/Babel   ( 6693): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 6422:com.motorola.context/u0a8 (adj 15): empty #7
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  307): CdmEngine::CloseSession
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  307): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  307): L3 Terminate.
D/DrmWidevineDash(  307): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  307): Service_Uninitialize: starts!
D/QSEECOMAPI: (  307): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  307): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  307): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6422/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6734): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6734): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6734): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6734): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6734): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6734):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6734):   adb logcat -s GAv4
,W/GAv4    ( 6734): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6763): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/GAv4    ( 6734): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6734): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6763): dex2oat took 98.681ms (threads: 4)
,I/Adreno-EGL( 6676): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6676): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6676): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6676): Local Branch: 
I/Adreno-EGL( 6676): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6676): Local Patches: NONE
I/Adreno-EGL( 6676): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6676): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6676): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6676): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6676): Local Branch: 
I/Adreno-EGL( 6676): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6676): Local Patches: NONE
I/Adreno-EGL( 6676): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ Nonce  ( 2587):  Nonce Reponse 
D/        ( 2587): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"1ed08db6-e370-4e50-baa5-8fe61c744b8f"}
D/MMApiWSBase( 2587): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2587):  Nonce Handle Reponse 
D/MMApiProvisionService( 2587): mOutstandingReq set to false
,I/WebViewFactory( 6734): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6734): Time to load native libraries: 1 ms (timestamps 9355-9356)
I/LibraryLoader( 6734): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6734): Binding Chromium to main looper Looper (main, tid 1) {27a6f257}
I/LibraryLoader( 6734): Expected native library version number "",actual native library version number ""
I/chromium( 6734): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6734): Initializing chromium process, singleProcess=true
W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6734): ApplicationContext is null in ApplicationStatus
,I/art     ( 2587): Explicit concurrent mark sweep GC freed 16565(990KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.310ms total 83.655ms
,W/chromium( 6734): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6734): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6734): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6734): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6734): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6734): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6734): Local Branch: 
I/Adreno-EGL( 6734): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6734): Local Patches: NONE
I/Adreno-EGL( 6734): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/MMApiProvisionService( 2587):  pTime 1452107623780 sExp 172742 cTime 1452267213170 tTime 1452280365780
,D/MMApiProvisionService( 2587):  No login Required 
,I/NSApplication( 6734): Starting up...
,W/AudioManagerAndroid( 6734): Requires BLUETOOTH permission
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6806 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6565:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 6676): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6676): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6676): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6676): Local Branch: 
I/Adreno-EGL( 6676): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6676): Local Patches: NONE
I/Adreno-EGL( 6676): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6565/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6676): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6676): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6676): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6676): Local Branch: 
I/Adreno-EGL( 6676): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6676): Local Patches: NONE
I/Adreno-EGL( 6676): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6236): Classify the device as Phone.
,W/DataUsage( 2587): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2587): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinTask( 6236): Sending checkin request (9528 bytes)
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6830 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6594:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6594/cgroup.procs: No such file or directory
,W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6853 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6875 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6653:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 6853): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/CheckinRequestBuilder( 6236): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  881): Killing 6621:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6653/cgroup.procs: No such file or directory
W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6621/cgroup.procs: No such file or directory
,E/ActivityThread( 6236): Failed to find provider info for com.google.android.wearable.settings
,I/MusicStore( 6875): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6875): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6875): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6875): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6875): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6875): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  881): Explicit concurrent mark sweep GC freed 9323(458KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.136ms total 115.780ms
,V/JNIHelp ( 6875): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinRequestBuilder( 6236): Classify the device as Phone.
,I/CheckinTask( 6236): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6236): Checking schedule, now: 1452267215023 next: 1452868352015
I/CheckinService( 6236): active receiver: disabled
,W/ActivityThread( 6875): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6875): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3644045e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6875): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6875): GMSCore installation verified
,D/CheckinService( 6236): Recording last checkin time for package unspecified as 1452267215033
,I/ConfigStore( 6875): Config Database version: 1
,I/ActivityManager(  881): Killing 6693:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6693/cgroup.procs: No such file or directory
,I/MediaRouter( 6875): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6875): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6875): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Killing 6734:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,E/libprocessgroup(  881): failed to kill 1 processes for processgroup 6734
,I/NetworkMonitor( 6875): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6934 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6875): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6875): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6806:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 6934): mnc/mcc: 
,V/Mms     ( 6934): tag: int value: recipientLimit - 20
V/Mms     ( 6934): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6934): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6934): tag: int value: maxSubjectLength - 80
V/Mms     ( 6934): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6934): tag: bool value: enableGroupMms - false
,V/Mms     ( 6934):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6806/cgroup.procs: No such file or directory
,W/ResourcesManager( 6934): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6970 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6830:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6830/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6970): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6970): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6970): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6853:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6853/cgroup.procs: No such file or directory
,I/CheckinService( 6236): Checkin interval check for package: unspecified last checkin: 1452267215033 min interval config: 0 actual interval: 1504
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6999 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 6236): Checking schedule, now: 1452267216593 next: 1452267245015
I/CheckinService( 6236): active receiver: disabled
,I/art     (  322): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.192ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 18.965ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.669ms
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7017 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6875:com.google.android.music:main/u0a80 (adj 13): empty #7
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310391, SEQNUM=4434, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-19631, POWER_SUPPLY_CHARGE_COUNTER=-647, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6875/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,W/ResourcesManager( 7017): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7017): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7017): MmsConfig.loadMmsSettings
I/Babel_SMS( 7017): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7017): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7017): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7017): MmsConfig.loadFromResources
E/Babel_SMS( 7017): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7017): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7017): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7017): startup - clean
,I/Babel   ( 7017): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7057 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7017): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7017): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7017): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7017): onServiceConnected
W/Babel   ( 7017): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7057): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7057): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7057): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7057):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7057):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7057): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7057): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7017): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 6934:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7057): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6934/cgroup.procs: No such file or directory
,W/GAv4    ( 7057): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7057): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7057): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7057): Time to load native libraries: 1 ms (timestamps 4654-4655)
I/LibraryLoader( 7057): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7057): Binding Chromium to main looper Looper (main, tid 1) {27a6f257}
I/LibraryLoader( 7057): Expected native library version number "",actual native library version number ""
I/chromium( 7057): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7057): Initializing chromium process, singleProcess=true
,W/art     ( 7057): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7057): ApplicationContext is null in ApplicationStatus
,W/chromium( 7057): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7057): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7057): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7057): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7057): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7057): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7057): Local Branch: 
I/Adreno-EGL( 7057): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7057): Local Patches: NONE
I/Adreno-EGL( 7057): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7057): Starting up...
,W/AudioManagerAndroid( 7057): Requires BLUETOOTH permission
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7120 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6970:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/jxcore-log( 6359): Test app app.js loaded
I/jxcore-log( 6359): 
,I/chromium( 6359): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6970/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7139 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6999:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6999/cgroup.procs: No such file or directory
,W/ResourcesManager( 7139): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7162 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7057:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 7162): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 7017:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7017/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2587): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7057/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2587): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2587): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2587): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2587): onServiceConnected()
,V/AlarmManager(  881): done {e5639d, *walarm*:com.google.android.intent.action.SEND_IDLE} [10031ms]
,D/GetNotificationsWS( 2587): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2587): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7191 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2587): started with background data enabled, making sure notification mechanism is enabled
,I/art     (  881): Explicit concurrent mark sweep GC freed 12234(622KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.566ms total 121.347ms
,D/LocationInitializer( 6236): Restart initialization of location
,D/WearableService( 1738): callingUid 10016, callindPid: 1738
,E/MDM     ( 1738): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1738): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7220 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1738): No location to return for getLastLocation()
,W/FusedLocationProvider( 1738): location=null
,I/MusicStore( 7220): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7220): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7220): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7220): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7220): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7220): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7220): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7220): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7220): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3644045e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7220): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7220): GMSCore installation verified
,I/ConfigStore( 7220): Config Database version: 1
,I/MediaRouter( 7220): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7220): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/NetworkMonitor( 7220): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7220): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7249 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7220): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7220): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6676:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7249): mnc/mcc: 
,V/Mms     ( 7249): tag: int value: recipientLimit - 20
V/Mms     ( 7249): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7249): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7249): tag: int value: maxSubjectLength - 80
V/Mms     ( 7249): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7249): tag: bool value: enableGroupMms - false
,V/Mms     ( 7249):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_6676/cgroup.procs: No such file or directory
,W/ResourcesManager( 7249): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7286 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7120:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7120/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7286): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7286): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7286): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 7139:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7139/cgroup.procs: No such file or directory
,I/CheckinService( 6236): Checkin interval check for package: unspecified last checkin: 1452267215033 min interval config: 0 actual interval: 5653
,I/CheckinService( 6236): Checkin interval check for package: unspecified last checkin: 1452267215033 min interval config: 0 actual interval: 5655
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/CheckinService( 6236): Checking schedule, now: 1452267220711 next: 1452267245015
I/CheckinService( 6236): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7306 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6236): Checking schedule, now: 1452267220772 next: 1452267245015
I/CheckinService( 6236): active receiver: disabled
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3bd02f90
,W/ResourcesManager( 7306): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GCoreNlp( 1738): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1569): Deferring update until onResume
,I/Babel_SMS( 7306): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7306): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7306): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7306): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7306): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7306): MmsConfig.loadFromResources
,E/Babel_SMS( 7306): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7306): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7306): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7306): startup - clean
,I/Babel   ( 7306): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7337 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 21.075ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 343us total 19.417ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 22.308ms
,W/VideoCapabilities( 7306): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7306): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7306): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7306): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7306): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7306): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7306): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7306): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7306): onServiceConnected
W/Babel   ( 7306): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7337): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7337): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7337):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7337):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7337): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7337): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7337): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7337): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7306): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 7162:android.process.acore/u0a7 (adj 15): empty #7
,W/GAv4    ( 7337): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7337): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7162/cgroup.procs: No such file or directory
,I/WebViewFactory( 7337): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7337): Time to load native libraries: 1 ms (timestamps 8029-8030)
I/LibraryLoader( 7337): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7337): Binding Chromium to main looper Looper (main, tid 1) {27a6f257}
I/LibraryLoader( 7337): Expected native library version number "",actual native library version number ""
,I/chromium( 7337): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7337): Initializing chromium process, singleProcess=true
,W/art     ( 7337): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7337): ApplicationContext is null in ApplicationStatus
,W/chromium( 7337): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7337): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7337): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7337): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7337): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7337): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7337): Local Branch: 
I/Adreno-EGL( 7337): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7337): Local Patches: NONE
I/Adreno-EGL( 7337): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7337): Requires BLUETOOTH permission
,I/NSApplication( 7337): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7404 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7220:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_7220/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7423 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7249:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_7249/cgroup.procs: No such file or directory
,I/art     (  881): Explicit concurrent mark sweep GC freed 18247(910KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.587ms total 130.418ms
,W/ResourcesManager( 7423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7446 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7191:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7286:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 7446): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2587): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7191/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7286/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2587): bindWebServices(): registering our AIDL callback...
I/SundryService( 2587): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2587): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2587): onServiceConnected()
D/GetNotificationsWS( 2587): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2587): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2587): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2587): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2587): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2587): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  881): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2587): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2587): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2587): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7476 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2587): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2587): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2587): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2587): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2587): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2587): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2587): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2587): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1414): onFinishInput()
W/IInputConnectionWrapper( 6359): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7476): Register our PhoneStateListener
,V/SetupWizard( 7476): Connected to Gservices successfully
,I/ActivityManager(  881): Killing 7306:com.google.android.talk/u0a70 (adj 15): empty #7
,I/LaunchCheckinHandler(  881): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,196
W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7306/cgroup.procs: No such file or directory
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7498 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7524 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7337:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7337/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7546 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7563 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7404:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7423:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7404/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7423/cgroup.procs: No such file or directory
,W/ResourcesManager( 7563): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 6201): Explicit concurrent mark sweep GC freed 3074(134KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 339us total 23.931ms
,I/Babel_SMS( 7563): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7563): MmsConfig.loadMmsSettings
I/Babel_SMS( 7563): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7563): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7563): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7563): MmsConfig.loadFromResources
E/Babel_SMS( 7563): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7563): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7563): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7563): startup - clean
,I/Babel   ( 7563): deleted: false for 0
,W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7596 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7563): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7563): Unsupported mime video/mpeg2
,W/asset   ( 7596): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7596): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7596): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7596): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7563): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6236): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2af0ec1c new=com.google.android.velvet.VelvetApplication@2af0ec1c
,I/UpdateIcingCorporaServi( 7524): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6236): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7627 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6236): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7627): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 7563): onServiceConnected
,W/Babel   ( 7563): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7563): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 7524): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
I/ActivityManager(  881): Killing 7476:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7476/cgroup.procs: No such file or directory
,V/JNIHelp ( 7563): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7563): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7563): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7662 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.151ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 18.891ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.370ms
,I/ActivityManager(  881): Killing 7498:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7498/cgroup.procs: No such file or directory
,D/Finsky  ( 7662): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7662): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7662): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7662): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7662): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7662): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7662): Skipping gmscore version check
,D/Finsky  ( 7662): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7662): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7708 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7546:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7546/cgroup.procs: No such file or directory
,I/art     (  881): Explicit concurrent mark sweep GC freed 12911(634KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.559ms total 114.014ms
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7731 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7596:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/Icing   ( 6236): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_7596/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7731): Register our PhoneStateListener
,I/ActivityManager(  881): Killing 7524:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/Icing   ( 6236): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6236): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7524/cgroup.procs: No such file or directory
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 6236): Checkin interval check for package: unspecified last checkin: 1452267215033 min interval config: 0 actual interval: 10989
,I/CheckinService( 6236): Checking schedule, now: 1452267226033 next: 1452267245015
I/CheckinService( 6236): active receiver: disabled
,I/ActivityManager(  881): Killing 7446:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7446/cgroup.procs: No such file or directory
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Killing 7627:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7627/cgroup.procs: No such file or directory
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/CheckinService( 6236): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310578, SEQNUM=4460, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-771, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {34f3053c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {285b831f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  881): send {1e50618, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  881): done {34f3053c, *alarm*:android.intent.action.TIME_TICK} [85ms]
,V/AlarmManager(  881): done {285b831f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [88ms]
,V/AlarmManager(  881): done {1e50618, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [94ms]
,I/CheckinService( 6236): Checkin interval check for package: unspecified last checkin: 1452267215033 min interval config: 0 actual interval: 46597
,I/CheckinService( 6236): Checking schedule, now: 1452267261645 next: 1452267245015
I/CheckinService( 6236): active receiver: enabled
,I/CheckinService( 6236): Preparing to send checkin request
,I/EventLogService( 6236): Accumulating logs since 1452267210850
,I/CheckinRequestBuilder( 6236): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6236): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7781 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7781): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7781): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7781): VM with version 2.1.0 has multidex support
I/MultiDex( 7781): install
,I/MultiDex( 7781): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7781): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7781): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7781): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3638e167: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7781): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1738): callingUid 10016, callindPid: 1738
,D/AuthorizationBluetoothService( 1738): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1738): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6236): Restart initialization of location
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1738): No location to return for getLastLocation()
,I/art     ( 7781): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/FusedLocationProvider( 1738): location=null
I/art     ( 7781): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7781): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  307): Instantiating CDM.
,I/WVCdm   (  307): CdmEngine::OpenSession
I/WVCdm   (  307): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  307): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  307): Service_Initialize: starts!
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
,D/QSEECOMAPI: (  307): Loaded image: APP id = 3
,D/DrmWidevineDash(  307): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
E/DrmWidevineDash(  307): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  307): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  307): OEMCrypto_OpenSession: starts! SID=0xb55b9960
D/DrmWidevineDash(  307): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: starts! randomData=0xb710db60, dataLength=8
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb71137a0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  307): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  307): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  307): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  307): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: starts! deviceID=0xb71fb750, idLength=0xbe9b12b0
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  307): PrepareKeyRequest: nonce=290859966
D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb70b4888
D/DrmWidevineDash(  307): message_length=1591, signature=0xb70b1538, signature_length=3197833876
,I/WVCdm   (  307): CdmEngine::OpenSession
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature returns 0
,D/DrmWidevineDash(  307): OEMCrypto_OpenSession: starts! SID=0xb55b9960
D/DrmWidevineDash(  307): OEMCrypto_OpenSession SID = 2
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: starts! randomData=0xb712ae20, dataLength=8
I/WVCdm   (  307): CdmEngine::CloseSession
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: starts!SID=2, wrapped_rsa_key=0xb71137a0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  307): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  307): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  307): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  307): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: starts! deviceID=0xb71fb770, idLength=0xb54b9730
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: starts! SID=2
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  307): PrepareKeyRequest: nonce=881138076
D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature starts! SID=2, message=0xb71132b0
D/DrmWidevineDash(  307): message_length=1626, signature=0xb70b1538, signature_length=3041629972
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  307): CdmEngine::CloseSession
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: starts! SID=2
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  307): L3 Terminate.
D/DrmWidevineDash(  307): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  307): Service_Uninitialize: starts!
D/QSEECOMAPI: (  307): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  307): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  307): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7822): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7822): dex2oat took 76.563ms (threads: 4)
,I/Adreno-EGL( 7781): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7781): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7781): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7781): Local Branch: 
I/Adreno-EGL( 7781): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7781): Local Patches: NONE
I/Adreno-EGL( 7781): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7781): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7781): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7781): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7781): Local Branch: 
I/Adreno-EGL( 7781): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7781): Local Patches: NONE
I/Adreno-EGL( 7781): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7781): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7781): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7781): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7781): Local Branch: 
I/Adreno-EGL( 7781): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7781): Local Patches: NONE
I/Adreno-EGL( 7781): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7781): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7781): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7781): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7781): Local Branch: 
I/Adreno-EGL( 7781): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7781): Local Patches: NONE
I/Adreno-EGL( 7781): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6236): Classify the device as Phone.
,I/CheckinTask( 6236): Sending checkin request (9523 bytes)
,I/CheckinRequestBuilder( 6236): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6236): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6236): Classify the device as Phone.
,I/CheckinTask( 6236): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6236): Checking schedule, now: 1452267264572 next: 1452868401565
I/CheckinService( 6236): active receiver: disabled
,D/CheckinService( 6236): Recording last checkin time for package unspecified as 1452267264601
,V/SetupWizard( 7731): Connected to Gservices successfully
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  881): Killing 7662:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_7662/cgroup.procs: No such file or directory
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7845 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Launcher( 1569): Deferring update until onResume
,I/art     ( 1738): Explicit concurrent mark sweep GC freed 97622(5MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 15MB/25MB, paused 1.122ms total 111.295ms
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@79f25fd
,I/GCoreNlp( 1738): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@310b36b9)
E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1888dafe)
,E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@372d25f)
E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@876b4ac)
E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e9f8575)
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7882 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7903 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7708:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7708/cgroup.procs: No such file or directory
,W/ResourcesManager( 7563): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 7903): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7926 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7731:com.google.android.setupwizard/u0a35 (adj 13): empty #7
,I/art     (  881): Explicit concurrent mark sweep GC freed 18321(961KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.584ms total 117.903ms
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7731/cgroup.procs: No such file or directory
,W/asset   ( 7926): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7926): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7926): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7926): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6236): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6236): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2af0ec1c new=com.google.android.velvet.VelvetApplication@2af0ec1c
,I/UpdateIcingCorporaServi( 7845): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6236): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7954 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7954): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7845): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
,W/art     ( 7954): No such thread id for suspend: 15
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7978 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7781:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_7781/cgroup.procs: No such file or directory
,D/Finsky  ( 7978): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7978): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7978): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7978): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7978): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7978): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7978): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 7978): Skipping gmscore version check
,D/Finsky  ( 7978): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 7882:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7882/cgroup.procs: No such file or directory
,I/Icing   ( 6236): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6236): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  881): Killing 7926:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_7926/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7563:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7563/cgroup.procs: No such file or directory
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1414): run()
,I/Keyboard.Facilitator( 1414): flushDynamicLanguageModels()
,I/ConfigService( 1738): onCreate
,I/ConfigService( 1738): onDestroy
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ClearcutLoggerApiImpl( 1738): disconnect managed GoogleApiClient
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309557, SEQNUM=4476, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-941, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): TAP version 13
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # multiplex can send data
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 3
,I/jxcore-log( 6359): ok 1 String should be length:200
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # basic
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 2 sane
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # another
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 3 sane
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): ok 4 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 5 null
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 6 (unnamed assert)
I/jxcore-log( 6359): 
I/jxcore-log( 6359): ok 7 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 8 should not throw
I/jxcore-log( 6359): 
I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 9 (unnamed assert)
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 10 (unnamed assert)
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 11 should not throw
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 12 should be equal
I/jxcore-log( 6359): 
I/jxcore-log( 6359): ok 13 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,V/AlarmManager(  881): send {34f3053c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {30d7447f, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {30d7447f, *walarm*:android.content.syncmanager.SYNC_ALARM} [14ms]
,V/AlarmManager(  881): done {34f3053c, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/jxcore-log( 6359): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): ok 14 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # failed to get mobile documents path
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 15 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 16 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 17 should be equal
I/jxcore-log( 6359): 
I/jxcore-log( 6359): ok 18 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # #init should register the networkChanged event
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 19 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # #startBroadcasting should throw on null device name
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): ok 20 should throw
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 21 should throw
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 22 should throw
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 23 should throw
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # #startBroadcasting should throw on negative port
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 24 should throw
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # #startBroadcasting should throw on too large port
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 25 should throw
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 26 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 27 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 28 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): ok 29 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 30 should be equal
I/jxcore-log( 6359): 
I/jxcore-log( 6359): ok 31 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): ok 32 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 33 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 34 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 35 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): ok 36 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 37 should be equal
I/jxcore-log( 6359): 
I/jxcore-log( 6359): ok 38 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 39 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 40 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): ok 41 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 42 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 43 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): ok 44 should be equal
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6359): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6359): 
,I/jxcore-log( 6359): # teardown
I/jxcore-log( 6359): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267558712.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558712.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267558712.6359
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558712.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558712.6359","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267558712.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@156708a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@156708a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
,D/WifiP2pService(  881): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
,I/jxcore-log( 6359): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
,D/WifiP2pService(  881): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
,D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  881): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
,I/jxcore-log( 6359): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267558893.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558893.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267558893.6359
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558893.6359","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558893.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267558893.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6ed45a12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6ed45a12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
I/wpa_supplicant( 1435): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  297): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/jxcore-log( 6359): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
I/jxcore-log( 6359): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267558944.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558944.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267558944.6359
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558944.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558944.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267558944.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@88f64d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@88f64d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/wpa_supplicant( 1435): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  297): Event received = P2P: Reject scan trigger 
I/jxcore-log( 6359): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
D/WifiP2pService(  881): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
I/jxcore-log( 6359): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267558983.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558983.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267558983.6359
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558983.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267558983.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267558983.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@badee292 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@badee292 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  297): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
I/jxcore-log( 6359): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/WifiP2pService(  881): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6359): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
D/WifiP2pService(  881): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559014.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559014.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559014.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559014.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559014.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267559014.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7991262e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7991262e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  297): Event received = P2P: Reject scan trigger 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
D/WifiP2pService(  881): discovery change broadcast true
I/jxcore-log( 6359): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/WifiP2pService(  881): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/jxcore-log( 6359): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559045.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559045.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559045.6359
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559045.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559045.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267559045.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2e7a44a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2e7a44a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  297): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/jxcore-log( 6359): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
D/WifiP2pService(  881): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/jxcore-log( 6359): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559071.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559071.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559071.6359
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559071.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559071.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267559071.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3805f4e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3805f4e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  297): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/jxcore-log( 6359): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
D/WifiP2pService(  881): remove client information from framework
I/jxcore-log( 6359): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
,D/WifiP2pService(  881): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559094.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559094.6359","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559094.6359
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559094.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559094.6359","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267559094.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ef88b41e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ef88b41e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
I/wpa_supplicant( 1435): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  297): Event received = P2P: Reject scan trigger 
I/jxcore-log( 6359): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
D/WifiP2pService(  881): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6359): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
,D/WifiP2pService(  881): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559117.6359
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559117.6359","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559117.6359
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559117.6359","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559117.6359","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267559117.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6e5f7c26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6e5f7c26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
I/wpa_supplicant( 1435): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-83
D/WifiP2pService(  881): discovery change broadcast true
D/TCMD    (  454): NL - Read 56 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  297): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,I/wpa_supplicant( 1435): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 6359): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
,I/io.jxcore.node.ConnectionHelper( 6359): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/WifiP2pService(  881): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1435): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/MDMCTBK (  297): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
D/WifiP2pService(  881): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
I/jxcore-log( 6359): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559150.6359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): bind: Binding a new listener
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559150.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6359): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): start: OK
I/io.jxcore.node.ConnectionHelper( 6359): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452267559150.6359
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6359): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559150.6359","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452267559150.6359","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452267559150.6359","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@eca5426c target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@eca5426c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): start: OK
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1435): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  297): Event received = P2P: Reject scan trigger 
I/jxcore-log( 6359): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6359): 
D/WifiP2pService(  881): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6359): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6359): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6359): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6359): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6359): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): stop: Stopping P2P device discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: NOT_INITIALIZED
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6359): release: No more listeners, de-initializing...
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6359): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6359): setState: NOT_STARTED
,I/wpa_supplicant( 1435): P2P-FIND-STOPPED 
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  297): Event received = P2P-FIND-STOPPED 
,I/jxcore-log( 6359): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6359): 
,D/WifiP2pService(  881): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
,I/jxcore-log( 6359): # setup
I/jxcore-log( 6359): 
,I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6359): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6359): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6359): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6359): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6359): Service requests cleared successfully
,I/wpa_supplicant( 1435): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-80
D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  297): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/TCMD    (  454): NL - Read 56 bytes from update socket.
D/TCMD    (  454): NL - message type is RTM_NEWLINK
D/TCMD    (  454): Listening for incoming client connection request
D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
,D/WifiP2pService(  881):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309731, SEQNUM=4488, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1188, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1435): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/MDMCTBK (  297): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  297): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  881): send {34f3053c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {12ba7594, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  881): send {306cc5b1, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  881): done {12ba7594, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [20ms]
,V/AlarmManager(  881): done {306cc5b1, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [53ms]
,V/AlarmManager(  881): done {34f3053c, *alarm*:android.intent.action.TIME_TICK} [66ms]
,I/EventLogService( 6236): Aggregate from 1452267261672 (log), 1452265976385 (data)
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  881): send {34f3053c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {3e807a22, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8107 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  881): done {34f3053c, *alarm*:android.intent.action.TIME_TICK} [97ms]
,I/GAv4    ( 8107): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8107):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8107):   adb logcat -s GAv4
,W/GAv4    ( 8107): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8107): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8107): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  881): done {3e807a22, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [296ms]
I/ActivityManager(  881): Killing 7845:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7845/cgroup.procs: No such file or directory
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  881): send {34f3053c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {1a368cb3, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  881): done {34f3053c, *alarm*:android.intent.action.TIME_TICK} [43ms]
,V/AlarmManager(  881): done {1a368cb3, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [94ms]
,I/GoogleURLConnFactory( 1738): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1738): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1738): Server returned 404
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=242, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309654, SEQNUM=4505, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-57, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  881): send {34f3053c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {30d7447f, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {30d7447f, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  881): done {34f3053c, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  881): send {34f3053c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {1bfadc34, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  881): done {1bfadc34, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [23ms]
,V/AlarmManager(  881): done {34f3053c, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  881): send {12ba7594, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,I/ProcessStatsService(  881): Prepared write state in 18ms
,V/AlarmManager(  881): send {2b116bf0, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  881): done {12ba7594, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [33ms]
,I/ProcessStatsService(  881): Prepared write state in 31ms
,V/AlarmManager(  881): done {2b116bf0, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [73ms]
,I/ProcessStatsService(  881): Pruning old procstats: /data/system/procstats/state-2016-01-07-20-16-56.bin
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  881): send {34f3053c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {371fafd2, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  881): send {2e7c08a3, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  881): send {268387a0, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  881): send {3f13af59, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  881): done {34f3053c, *alarm*:android.intent.action.TIME_TICK} [50ms]
,V/AlarmManager(  881): done {371fafd2, *walarm*:com.motorola.ccc.cce.alarmintent} [127ms]
,V/AlarmManager(  881): done {2e7c08a3, *walarm*:com.motorola.ccc.cce.alarmintent} [142ms]
,V/AlarmManager(  881): done {268387a0, *walarm*:com.motorola.ccc.cce.alarmintent} [161ms]
,V/AlarmManager(  881): done {3f13af59, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [168ms]
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8219): 
D/AndroidRuntime( 8219): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8219): CheckJNI is OFF
D/AndroidRuntime( 8219): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10422 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6359:com.test.thalitest/u0a422 (adj 9): stop com.test.thalitest
W/PackageSettings(  881): Skipping PackageSetting{345c074b com.example.hello/10420} due to missing metadata
I/WindowState(  881): WIN DEATH: Window{146042ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  881): Client connection lost with reason: 4
I/ActivityManager(  881):   Force finishing activity ActivityRecord{1e3ad954 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  881): Spurious death for ProcessRecord{bd818d0 6359:com.test.thalitest/u0a422}, curProc for 6359: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10422 user=0: pkg removed
I/ActivityManager(  881):   Force finishing activity ActivityRecord{1e3ad954 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{1e3ad954 u0 com.test.thalitest/.MainActivity t3 f}
W/GeofencerStateMachine( 1738): Ignoring removeGeofence because network location is disabled.
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1414): resetDictionaries() : en_US
I/art     ( 3041): Explicit concurrent mark sweep GC freed 10923(2MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 7MB/12MB, paused 836us total 48.669ms
D/VoicemailCleanupService( 7903): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1414): run()
I/Decoder ( 1414): createOrResetDecoder
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8248 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  322): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 26.448ms
I/art     ( 1569): Explicit concurrent mark sweep GC freed 5081(313KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 599us total 128.407ms
I/art     (  322): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 19.694ms
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.589ms
I/art     (  881): Explicit concurrent mark sweep GC freed 38310(2MB) AllocSpace objects, 11(263KB) LOS objects, 33% free, 20MB/30MB, paused 4.081ms total 170.517ms
I/art     (  881): WaitForGcToComplete blocked for 60.958ms for cause Explicit
I/ConfigService( 1738): onCreate
W/asset   ( 8248): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8248): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8248): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8248): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1414): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1414): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1414): run()
I/StatsUtilsManager( 1414): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1414): shouldRecordStats() = Too Soon
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8273 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  881): Killing 7954:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  881): Explicit concurrent mark sweep GC freed 7914(456KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.600ms total 215.665ms
W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7954/cgroup.procs: No such file or directory
I/Launcher( 1569): Deferring update until onResume
W/ContextImpl( 8273): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6236): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AndroidRuntime( 8219): Shutting down VM
D/AccountUtils( 6236): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6236): Reading stored module config
D/ChimeraCfgMgr( 6236): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6236): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6236): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6236): App measurement is starting up, version: 8489
I/GMPM-SVC( 6236): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1738): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1738): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6236): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6236): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6236): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6236): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6236): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6236): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6236): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6236): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6236): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6236): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6236): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6236): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6236): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8306 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 6236): doRemovePackageData com.test.thalitest
W/BaseAppContext( 6236): Using Auth Proxy for data requests.
W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2af0ec1c new=com.google.android.velvet.VelvetApplication@2af0ec1c
D/ChimeraCfgMgr( 6236): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6236): Module APK com.google.android.play.games already loaded
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8328 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/BaseAppContext( 6236): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
E/SQLiteLog( 6236): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/BaseAppContext( 6236): Using Auth Proxy for data requests.
--------- beginning of crash
E/AndroidRuntime( 6236): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6236): Process: com.google.android.gms, PID: 6236
E/AndroidRuntime( 6236): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6236): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6236): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6236): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6236): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6236): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6236): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6236): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6236): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6236): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6236): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6236): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6236): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6236): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 6236): Sending signal. PID: 6236 SIG: 9
D/WifiService(  881): Client connection lost with reason: 4
I/ActivityManager(  881): Process com.google.android.gms (pid 6236) has died
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 11000ms
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
