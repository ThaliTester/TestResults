#### Test 564317025f150b2_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/AndroidRuntime( 6454): 
D/AndroidRuntime( 6454): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6454): CheckJNI is OFF
D/AndroidRuntime( 6454): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  878): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6473 uid=10464 gids={50464, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6454): Shutting down VM
V/ActivityManager(  878): Display changed displayId=0
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6473): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6473): Time to load native libraries: 5 ms (timestamps 7593-7598)
I/LibraryLoader( 6473): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6473): Binding Chromium to main looper Looper (main, tid 1) {2a726031}
,I/LibraryLoader( 6473): Expected native library version number "",actual native library version number ""
,I/chromium( 6473): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6473): Initializing chromium process, singleProcess=true
,W/art     ( 6473): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6473): ApplicationContext is null in ApplicationStatus
,W/chromium( 6473): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6473): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6473): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6473): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6473): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6473): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6473): Local Branch: 
I/Adreno-EGL( 6473): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6473): Local Patches: NONE
I/Adreno-EGL( 6473): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  878): Activity pause timeout for ActivityRecord{2bc9efdd u0 com.test.thalitest/.MainActivity t6}
,D/BluetoothManagerService(  878): Message: 20
,D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a8a1e38:true
,W/art     ( 6473): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6473): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6473): CordovaWebView is running on device made by: motorola
W/art     ( 6473): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6473): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6473): Render dirty regions requested: true
D/Atlas   ( 6473): Validating map...
W/chromium( 6473): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6473): Initialized EGL, version 1.4
D/OpenGLRenderer( 6473): Enabling debug mode 0
I/Keyboard.Facilitator( 1417): onFinishInput()
I/LaunchCheckinHandler(  878): Displayed com.test.thalitest/.MainActivity,cp,ca,1034
I/ActivityManager(  878): Displayed com.test.thalitest/.MainActivity: +967ms (total +1s34ms)
W/IInputConnectionWrapper( 6473): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6473): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6473): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6473): Cannot call determinedVisibility() - never saw a connection for the pid: 6473
D/JsMessageQueue( 6473): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6473): JniHelper::setJavaVM(0xb7a50310), pthread_self() = -1210180088
D/JX-Cordova( 6473): jxcore cordova android initializing
I/io.jxcore.node.ConnectionHelper( 6473): Build version SDK_INT: 21
,W/jxcore-log( 6473): Initializing JXcore engine
W/jxcore-log( 6473): JXcore engine is ready
,W/jxcore-log( 6473): Starting JXcore engine
,W/.test.thalitest( 6473): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10464 path="socket:[5694]" dev="sockfs" ino=5694 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6473): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10464 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6473): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10464 path="socket:[9474]" dev="sockfs" ino=9474 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6473): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10464 path="socket:[26511]" dev="sockfs" ino=26511 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6473): Platform android
W/jxcore-log( 6473): 
W/jxcore-log( 6473): Process ARCH arm
W/jxcore-log( 6473): 
,I/jxcore-log( 6473): JXcore Cordova bridge is ready!
I/jxcore-log( 6473): 
W/jxcore-log( 6473): JXcore engine is started
,I/chromium( 6473): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6473): Toggling radios to true
I/jxcore-log( 6473): 
,D/BluetoothAdapter( 6473): enable(): BT is already enabled..!
,D/WifiService(  878): New client listening to asynchronous messages
,D/WifiService(  878): setWifiEnabled: true pid=6473, uid=10464
E/WifiService(  878): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6473): Radios toggled
I/jxcore-log( 6473): 
I/jxcore-log( 6473): My device name is: motorola-XT1072
I/jxcore-log( 6473): 
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  305): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  305):  STA Disconnected !!
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): get_property_value, Enter
I/MDMCTBK (  305): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  305): get_property_value, Exit
I/MDMCTBK (  305): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  305): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  305): set_property_value, Enter
I/MDMCTBK (  305): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  466): NL - Read 1004 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
I/MDMCTBK (  305): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  305): set_property_value, Exit
I/MDMCTBK (  305): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  305): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  305): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  305): set_property_value, Enter
I/MDMCTBK (  305): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  305): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  305): set_property_value, Exit
E/MDMCTBK (  305): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  305): Event received = CTRL-EVENT-REGDOM-CHANGE
D/Tethering(  878): InitialState.processMessage what=4
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  305): Event received = CTRL-EVENT-REGDOM-CHANGE
W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
D/Tethering(  878):  0
E/WifiStateMachine(  878): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  878): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  878): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  303): Clearing all IP addresses on wlan0
,D/TCMD    (  466): NL - Read 60 bytes from update socket.
D/TCMD    (  466): NL - ignore NL message, type = 21
D/TCMD    (  466): Listening for incoming client connection request
,V/NativeCrypto( 1753): Read error: ssl=0xb7d1c6e0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1753): SSL shutdown failed: ssl=0xb7d1c6e0: I/O error during system call, Broken pipe
,D/ConnectivityService(  878): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiMetrics(  878): connected time updated 121344
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager(  878): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6550 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  878): Start Disconnecting Watchdog 1
,D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  305): Event received = CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService(  878): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  878): ConnectModeState: Network connection lost 
D/Nat464Xlat(  878): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  878): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/ConnectivityService(  878): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Disconnected - quitting
D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524292
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=null
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/CommandListener(  303): Clearing all IP addresses on wlan0
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  878): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  878): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  878): Explicit concurrent mark sweep GC freed 49227(2MB) AllocSpace objects, 3(228KB) LOS objects, 33% free, 20MB/30MB, paused 2.093ms total 145.472ms
,W/ResourcesManager( 6550): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6578 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  305): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  466): NL - Read 56 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/TCMD    (  466): Listening for incoming client connection request
D/MDMCTBK (  305): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  878): [1,453,190,830,798 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1408): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  878): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  305): Event received = Trying to associate with
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1408): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  878): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@15a2e555 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  878): Killing 6179:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
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
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1408): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  305): Event received = Associated with c0:ff:d4
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
,D/TCMD    (  466): NL - Read 80 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 80 bytes from update socket.
,D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
D/TCMD    (  466): NL - Read 68 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,D/Tethering(  878): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
E/Tethering(  878): ApnList is empty for checkDunConfigured()
,D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  0
I/wpa_supplicant( 1408): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  305): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  305): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  305):  STA Connected !!
D/TCMD    (  466): NL - Read 1004 bytes from update socket.
D/TCMD    (  466): NL - message type is RTM_NEWLINK
D/TCMD    (  466): Listening for incoming client connection request
,E/MDMCTBK (  305): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  305): get_freq !!, resp=2412
I/MDMCTBK (  305): get_freq !!, Strip data
I/MDMCTBK (  305): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): get_property_value, Enter
I/MDMCTBK (  305): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  305): get_property_value, Exit
I/MDMCTBK (  305): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  305): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  305): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  305): set_property_value, Enter
I/MDMCTBK (  305): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  305): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  305): set_property_value, Exit
I/MDMCTBK (  305): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  305): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  305): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): get_property_value, Enter
I/MDMCTBK (  305): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  305): get_property_value, Exit
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
I/MDMCTBK (  305): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1194967736
I/MDMCTBK (  305): return from set_get_from_wpa_supplicant
I/MDMCTBK (  305): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  305): set_property_value, Enter
I/MDMCTBK (  305): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  305): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  305): set_property_value, Exit
E/MDMCTBK (  305): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  305): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  305): , reply_len: 3, ret: 0
E/MDMCTBK (  305): MdmCutbackHndler, resp=OK
E/MDMCTBK (  305): 
D/MDMCTBK (  305): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
W/libprocessgroup(  878): failed to open /acct/uid_10057/pid_6179/cgroup.procs: No such file or directory
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  878): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  878): Network connection established
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  878): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  878): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  878): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  878): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  303): Setting iface cfg
E/WifiStateMachine(  878): Start Dhcp Watchdog 2
E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  878): do suspend false
W/ResourcesManager( 6578): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  878): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  878): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25dec551 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25dec551 target=com.android.internal.util.StateMachine$SmHandler }
,I/PhenotypeConfigurator( 1753): Scheduling Phenotype for one-off execution 12638 seconds from now (1453190831083)
,D/GetConfigurationSnapshotOperation( 1753): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1753): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1753): Using platform SSLCertificateSocketFactory
,I/Babel_SMS( 6578): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6578): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6578): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6578): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6578): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6578): MmsConfig.loadFromResources
E/Babel_SMS( 6578): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6578): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,E/DHCPCD  ( 6618): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6618): version 5.5.6 starting
E/DHCPCD  ( 6618): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6618): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6618): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6618): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6618): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6618): wlan0: sending REQUEST (xid 0xc7d4f15), next in 4.56 seconds
,W/Settings( 6578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6578): startup - clean
,I/Babel   ( 6578): deleted: false for 0
,D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,W/AudioCapabilities( 6578): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6578): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6578): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  878): Killing 6231:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_6231/cgroup.procs: No such file or directory
,I/vclib   ( 6578): onServiceConnected
W/Babel   ( 6578): Attempted to change video mute state without an active call.
,D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1753): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/DHCPCD  ( 6618): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6618): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6618): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 6618): wlan0: adding route to 192.168.1.0/24
,D/DHCPCD  ( 6618): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6618): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  466): NL - Read 60 bytes from update socket.
D/TCMD    (  466): NL - ignore NL message, type = 20
D/TCMD    (  466): Listening for incoming client connection request
,D/DHCPCD  ( 6618): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  878): WifiStateMachine DHCP successful
E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  878): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  878): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  878): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): ConnectedState Enter  mScreenOn=false scanperiod=20000
,E/ConnectivityService(  878): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  878): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  878): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  878): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  878): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878):    accepting network in place of null
D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  878): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 08:07:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453190833269], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453190833255]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Validated
D/ConnectivityService(  878): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  878): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  878): MasterInitialState.processMessage what=3
D/Tethering(  878): MasterInitialState.processMessage what=3
,D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6684 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1461): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2631): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2631): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2631): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2631): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2631): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2631): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2631): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2631): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2631): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2631): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2631): [debug] > CusSM.onRadioDown
,E/global frequency( 2631): no tags to log
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  878): send {364cd4b2, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  878): send {19ba90ff, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/MusicStore( 6684): Database version: 120
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  878): done {364cd4b2, *alarm*:android.intent.action.TIME_TICK} [34ms]
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6684): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6684): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 56732(3MB) AllocSpace objects, 35(1184KB) LOS objects, 40% free, 7MB/12MB, paused 1.126ms total 47.437ms
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/ActivityThread( 6684): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6684): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fb67e9d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6684): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6684): GMSCore installation verified
,I/ConfigStore( 6684): Config Database version: 1
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  878): send {2d83d27d, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/art     (  878): Explicit concurrent mark sweep GC freed 35089(1770KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.587ms total 122.286ms
,D/ConnectivityService(  878): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/MediaRouter( 6684): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6684): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/art     ( 2631): Explicit concurrent mark sweep GC freed 51215(2MB) AllocSpace objects, 6(142KB) LOS objects, 40% free, 11MB/19MB, paused 1.141ms total 89.793ms
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/NetworkMonitor( 6684): type=WIFI subType= reason=null isConnected=true
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2631): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2631): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2631): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2631): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/NetworkMonitor( 6684): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6719 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/global frequency( 2631): BcsDSCheckin.events found events 186
D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/GHttpClientFactory( 6684): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6684): Using platform SSLCertificateSocketFactory
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ActivityManager(  878): Killing 6023:android.process.acore/u0a7 (adj 15): empty #7
,D/MMApiWebService( 2631): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,V/Mms     ( 6719): mnc/mcc: 
V/Mms     ( 6719): tag: int value: recipientLimit - 20
,V/Mms     ( 6719): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6719): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6719): tag: int value: maxSubjectLength - 80
V/Mms     ( 6719): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6719): tag: bool value: enableGroupMms - false
V/Mms     ( 6719):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MMApiWSBase( 2631): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_6023/cgroup.procs: No such file or directory
,W/ResourcesManager( 6719): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6754 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 24.853ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 19.786ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 22.188ms
,I/ActivityManager(  878): Killing 6100:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6754): Register our PhoneStateListener
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_6100/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6754): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6754): onReceive CONNECTIVITY_CHANGE networkType=1
,I/jxcore-log( 6473): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6473): 
,I/ActivityManager(  878): Killing 6578:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_6578/cgroup.procs: No such file or directory
,I/CheckinService( 6315): Checkin interval check for package: unspecified last checkin: 1453190751926 min interval config: 0 actual interval: 83478
,I/CheckinService( 6315): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6315): SYNC; picasa accounts
,I/CheckinService( 6315): Checking schedule, now: 1453190835458 next: 1453190781900
I/CheckinService( 6315): active receiver: enabled
,D/NetworkLogImpl( 6315): Loaded NetworkSpeedPredictor
,I/CheckinService( 6315): Preparing to send checkin request
,I/iu.Environment( 6315): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6315): Accumulating logs since 1453190748895
,I/iu.UploadsManager( 6315): num queued entries: 0
I/iu.UploadsManager( 6315): num updated entries: 0
I/iu.SyncManager( 6315): NEXT; no task
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6804 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6315): Checkin reason type: 8 attempt count: 1
,D/WifiService(  878): New client listening to asynchronous messages
,E/ActivityThread( 6315): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 6473): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6473): 
,I/jxcore-log( 6473): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6473): 
D/MMApiWSBase( 2631): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2631): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2631): AppWSProxy - sendAIDLWSResponse() sending reponse
I/global frequency( 2631): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6827 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/jxcore-log( 6473): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6473): 
,D/CheckinProvider(  878): 186 events delete 0 left
,I/jxcore-log( 6473): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6473): 
,I/jxcore-log( 6473): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6473): 
,I/jxcore-log( 6473): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6473): 
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6844 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6827): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6827): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1461): now: 198177 ,futureTime: 86475386
D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1461): Polling alarm set to expire at: 86475386 Current Time: 198177
,D/PollingManager( 2631): now: 198177 ,futureTime: 9223372036854775807
D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2631): now: 198178 ,futureTime: 9223372036854775807
D/PollingManager( 2631): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2631): now: 198178 ,futureTime: 9223372036854775807
D/OtaApp  ( 2631): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6684): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2631): [debug] > PollingManagerService, now: 198185 ,futureTime: 20191199
D/OtaApp  ( 2631): [debug] > Polling alarm set to expire at: 20191199 Current Time: 198186
,I/MultiDex( 6827): VM with version 2.1.0 has multidex support
I/MultiDex( 6827): install
I/MultiDex( 6827): VM has multidex support, MultiDex support library is disabled.
,D/MMApiProvisionService( 2631): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2631): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2631): createDeviceIdOrLogin update_device
D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2631): Not proxy app, so login/provision not allowed
,V/JNIHelp ( 6827): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     (  878): Explicit concurrent mark sweep GC freed 10747(507KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.308ms total 151.261ms
I/global frequency( 2631): BcsDSCheckin.events found events 0
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 4010(175KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 819us total 31.928ms
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiProvisionService( 2631): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2631): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2631): createDeviceIdOrLogin update_device
,D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
,W/ActivityThread( 6827): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6827): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c5b8f5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6827): Installed default security provider GmsCore_OpenSSL
,D/MMApiProvisionService( 2631): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2631): set mOutstandingReq to true.
I/ Nonce  ( 2631):  Nonce getNonce 
I/ Nonce  ( 2631):  Nonce Request 
,I/ Nonce  ( 2631):  Nonce execute Request 
,D/MMApiWebService( 2631): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2631): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2631): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2631): createDeviceIdOrLogin update_device
D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2631): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2631): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2631): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2631): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2631): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2631): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2631): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2631): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2631): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2631): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
D/OtaApp  ( 2631): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 6827): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6827): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/MMApiWebService( 2631): generating token using payload instead of using session token
W/DataUsage( 2631): invalid counter update blocked: 'err' by 0
D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 6263): WaitForGcToComplete blocked for 9.798ms for cause DisableMovingGc
,D/ Nonce  ( 2631):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2631): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
,D/NativeLibraryUtils( 6827): Install completed successfully. count=14 extracted=0
,I/Babel_SMS( 6844): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6844): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6844): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6844): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6844): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6844): MmsConfig.loadFromResources
E/Babel_SMS( 6844): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6844): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
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
D/DrmWidevineDash(  307): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
E/DrmWidevineDash(  307): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: starts!
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  307): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: starts! SID=0xae21d960
D/DrmWidevineDash(  307): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: starts! randomData=0xb877f320, dataLength=8
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb886b5f0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  307): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  307): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  307): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  307): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: starts! deviceID=0xb88b89e8, idLength=0xbecd82b0
D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  307): PrepareKeyRequest: nonce=2288306255
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb87727b8
D/DrmWidevineDash(  307): message_length=1591, signature=0xb87d3500, signature_length=3201139348
,I/jxcore-log( 6473): Test app app.js loaded
I/jxcore-log( 6473): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6473): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6473): BLE advertisement is supported
I/jxcore-log( 6473): 
,I/chromium( 6473): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/Settings( 6844): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6844): startup - clean
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  307): CdmEngine::CloseSession
,D/DrmWidevineDash(  307): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  307): L3 Terminate.
D/DrmWidevineDash(  307): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  307): Service_Uninitialize: starts!
D/QSEECOMAPI: (  307): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  307): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  307): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_Terminate: ends! returns 0
,I/Babel   ( 6844): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6878 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6844): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6844): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6844): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6844): onServiceConnected
,W/Babel   ( 6844): Attempted to change video mute state without an active call.
,I/Babel   ( 6844): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 6550:com.motorola.context/u0a8 (adj 15): empty #7
,I/ Nonce  ( 2631):  Nonce Reponse 
D/        ( 2631): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"e7cdae5f-98bb-40a3-8830-a364c2d33359"}
D/MMApiWSBase( 2631): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2631):  Nonce Handle Reponse 
D/MMApiProvisionService( 2631): mOutstandingReq set to false
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_6550/cgroup.procs: No such file or directory
,D/MMApiProvisionService( 2631):  pTime 1453032756427 sExp 172742 cTime 1453190837353 tTime 1453205498427
,D/MMApiProvisionService( 2631):  No login Required 
,I/dex2oat ( 6899): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6878): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6878): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6878): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6878): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/dex2oat ( 6899): dex2oat took 146.921ms (threads: 4)
,I/GAv4    ( 6878): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6878):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6878):   adb logcat -s GAv4
,I/Adreno-EGL( 6827): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6827): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6827): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6827): Local Branch: 
I/Adreno-EGL( 6827): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6827): Local Patches: NONE
I/Adreno-EGL( 6827): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 6878): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6878): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6878): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6827): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6827): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6827): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6827): Local Branch: 
I/Adreno-EGL( 6827): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6827): Local Patches: NONE
I/Adreno-EGL( 6827): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  307): CdmEngine::OpenSession
I/WVCdm   (  307): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  307): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  307): Service_Initialize: starts!
,D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
,D/QSEECOMAPI: (  307): Loaded image: APP id = 3
,D/DrmWidevineDash(  307): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,E/DrmWidevineDash(  307): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  307): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: starts! SID=0xb1393960
D/DrmWidevineDash(  307): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: starts! randomData=0xb87f1d00, dataLength=8
,D/DrmWidevineDash(  307): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb886b5f0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  307): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  307): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  307): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  307): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: starts! deviceID=0xb88b8a28, idLength=0xae21d730
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  307): PrepareKeyRequest: nonce=637170822
D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb87727b8
D/DrmWidevineDash(  307): message_length=1626, signature=0xb8772e18, signature_length=2921453332
,I/WebViewFactory( 6878): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/DataUsage( 2631): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
,I/LibraryLoader( 6878): Time to load native libraries: 1 ms (timestamps 9856-9857)
I/LibraryLoader( 6878): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6878): Binding Chromium to main looper Looper (main, tid 1) {1e6830a}
I/LibraryLoader( 6878): Expected native library version number "",actual native library version number ""
I/chromium( 6878): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6878): Initializing chromium process, singleProcess=true
W/art     ( 6878): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6878): ApplicationContext is null in ApplicationStatus
,W/chromium( 6878): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6878): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6878): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6878): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6878): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6878): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6878): Local Branch: 
I/Adreno-EGL( 6878): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6878): Local Patches: NONE
I/Adreno-EGL( 6878): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  307): CdmEngine::CloseSession
,D/DrmWidevineDash(  307): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  307): L3 Terminate.
D/DrmWidevineDash(  307): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  307): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  307): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  307): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  307): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 6878): Requires BLUETOOTH permission
,I/NSApplication( 6878): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6951 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6684:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 6827): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6827): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6827): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6827): Local Branch: 
I/Adreno-EGL( 6827): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6827): Local Patches: NONE
I/Adreno-EGL( 6827): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_6684/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6827): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6827): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6827): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6827): Local Branch: 
I/Adreno-EGL( 6827): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6827): Local Patches: NONE
I/Adreno-EGL( 6827): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6315): Classify the device as Phone.
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6985 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 6719:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_6719/cgroup.procs: No such file or directory
,W/ResourcesManager( 6985): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinTask( 6315): Sending checkin request (9446 bytes)
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7005 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7026 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 6804:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 7005): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 6754:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_6804/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_6754/cgroup.procs: No such file or directory
,I/MusicStore( 7026): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7026): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7026): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7026): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7026): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7026): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7026): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7026): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7026): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fb67e9d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7026): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7026): GMSCore installation verified
,I/ConfigStore( 7026): Config Database version: 1
,I/CheckinRequestBuilder( 6315): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6315): Failed to find provider info for com.google.android.wearable.settings
,I/MediaRouter( 7026): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7026): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7026): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7026): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7057 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7026): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7026): Using platform SSLCertificateSocketFactory
,I/art     (  878): Explicit concurrent mark sweep GC freed 10465(509KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.122ms total 163.607ms
,I/ActivityManager(  878): Killing 6844:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7057): mnc/mcc: 
,V/Mms     ( 7057): tag: int value: recipientLimit - 20
V/Mms     ( 7057): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7057): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7057): tag: int value: maxSubjectLength - 80
V/Mms     ( 7057): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7057): tag: bool value: enableGroupMms - false
V/Mms     ( 7057):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_6844/cgroup.procs: No such file or directory
,W/ResourcesManager( 7057): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7093 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6878:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_6878/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7093): Register our PhoneStateListener
,I/CheckinRequestBuilder( 6315): Classify the device as Phone.
,D/MobileConnectivityChangeReceiver( 7093): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7093): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 6951:com.android.chrome/u0a52 (adj 15): empty #7
,I/CheckinTask( 6315): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_6951/cgroup.procs: No such file or directory
,I/CheckinService( 6315): Checkin interval check for package: unspecified last checkin: 1453190751926 min interval config: 0 actual interval: 88171
,I/CheckinService( 6315): Checking schedule, now: 1453190840098 next: 1453190870067
,I/CheckinService( 6315): active receiver: disabled
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7115 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6315): Checking schedule, now: 1453190840175 next: 1453190870067
,I/CheckinService( 6315): active receiver: disabled
,D/CheckinService( 6315): Recording last checkin time for package unspecified as 1453190840180
,I/ActivityManager(  878): Killing 6985:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 27.337ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 20.766ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.153ms
,I/ActivityManager(  878): Killing 7005:android.process.acore/u0a7 (adj 15): empty #8
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=288, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310908, SEQNUM=4475, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-319, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_6985/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7005/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2485): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2485): Disconnected process message: 10, size: 0
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7135 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  878): Killing 7026:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_7026/cgroup.procs: No such file or directory
,W/ResourcesManager( 7135): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7135): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7135): MmsConfig.loadMmsSettings
I/Babel_SMS( 7135): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7135): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7135): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7135): MmsConfig.loadFromResources
,E/Babel_SMS( 7135): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7135): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7135): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7135): startup - clean
,I/Babel   ( 7135): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7162 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7135): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7135): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7135): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7135): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7135): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7135): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7135): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7135): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7135): onServiceConnected
W/Babel   ( 7135): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7162): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/Babel   ( 7135): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  878): Killing 7057:com.android.mms/u0a23 (adj 13): empty #7
I/GAv4    ( 7162): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7162):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7162):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7162): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7162): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7162): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_7057/cgroup.procs: No such file or directory
,W/GAv4    ( 7162): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7162): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7162): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7162): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7162): Time to load native libraries: 2 ms (timestamps 3624-3626)
,I/LibraryLoader( 7162): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7162): Binding Chromium to main looper Looper (main, tid 1) {1e6830a}
I/LibraryLoader( 7162): Expected native library version number "",actual native library version number ""
I/chromium( 7162): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7162): Initializing chromium process, singleProcess=true
,W/art     ( 7162): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7162): ApplicationContext is null in ApplicationStatus
,W/chromium( 7162): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7162): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7162): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7162): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7162): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7162): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7162): Local Branch: 
I/Adreno-EGL( 7162): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7162): Local Patches: NONE
I/Adreno-EGL( 7162): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7162): Requires BLUETOOTH permission
,I/NSApplication( 7162): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7230 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7093:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7093/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7249 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 7115:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7115/cgroup.procs: No such file or directory
,W/ResourcesManager( 7249): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7272 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7162:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7272): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 7135:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2631): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_7162/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7135/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2631): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2631): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2631): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2631): onServiceConnected()
,V/AlarmManager(  878): done {19ba90ff, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [8913ms]
D/GetNotificationsWS( 2631): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2631): unbindWebServices(): un-registering our AIDL callback...
,V/AlarmManager(  878): done {2d83d27d, *walarm*:com.google.android.intent.action.SEND_IDLE} [8523ms]
,I/PushService( 2631): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7304 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7328 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6827:com.google.android.gms.unstable/u0a16 (adj 13): empty #7
,I/MusicStore( 7328): Database version: 120
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_6827/cgroup.procs: No such file or directory
W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7328): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7328): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7328): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7328): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7328): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7328): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7328): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7328): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fb67e9d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7328): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7328): GMSCore installation verified
,I/ConfigStore( 7328): Config Database version: 1
,I/art     (  878): Explicit concurrent mark sweep GC freed 13494(697KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.614ms total 111.548ms
,I/MediaRouter( 7328): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7328): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7328): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7328): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7359 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7328): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7328): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 7230:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7359): mnc/mcc: 
,V/Mms     ( 7359): tag: int value: recipientLimit - 20
,V/Mms     ( 7359): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7359): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7359): tag: int value: maxSubjectLength - 80
V/Mms     ( 7359): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7359): tag: bool value: enableGroupMms - false
,V/Mms     ( 7359):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_7230/cgroup.procs: No such file or directory
,W/ResourcesManager( 7359): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7394 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7249:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7394): Register our PhoneStateListener
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7249/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7394): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7394): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6315): Checkin interval check for package: unspecified last checkin: 1453190840180 min interval config: 0 actual interval: 3647
,I/CheckinService( 6315): Checkin interval check for package: unspecified last checkin: 1453190840180 min interval config: 0 actual interval: 3648
,I/CheckinService( 6315): Checking schedule, now: 1453190843834 next: 1453190870067
I/CheckinService( 6315): active receiver: disabled
,I/CheckinService( 6315): Checking schedule, now: 1453190843844 next: 1453190870067
I/CheckinService( 6315): active receiver: disabled
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7417 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7272:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7272/cgroup.procs: No such file or directory
,W/ResourcesManager( 7417): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7417): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7417): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7417): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7417): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7417): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7417): MmsConfig.loadFromResources
E/Babel_SMS( 7417): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7417): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7417): startup - clean
,I/Babel   ( 7417): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7452 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.934ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 19.218ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.961ms
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7417): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7417): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7417): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7452): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 7452): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7452):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7452):   adb logcat -s GAv4
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7452): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/vclib   ( 7417): onServiceConnected
W/Babel   ( 7417): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7452): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7452): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7452): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7452): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7452): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7417): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 7328:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_7328/cgroup.procs: No such file or directory
,I/WebViewFactory( 7452): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7452): Time to load native libraries: 2 ms (timestamps 7023-7025)
I/LibraryLoader( 7452): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7452): Binding Chromium to main looper Looper (main, tid 1) {1e6830a}
I/LibraryLoader( 7452): Expected native library version number "",actual native library version number ""
I/chromium( 7452): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7452): Initializing chromium process, singleProcess=true
,W/art     ( 7452): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7452): ApplicationContext is null in ApplicationStatus
,W/chromium( 7452): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7452): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7452): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7452): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7452): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7452): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7452): Local Branch: 
I/Adreno-EGL( 7452): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7452): Local Patches: NONE
I/Adreno-EGL( 7452): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7452): Starting up...
,W/AudioManagerAndroid( 7452): Requires BLUETOOTH permission
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7524 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7359:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_7359/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7543 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7394:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7394/cgroup.procs: No such file or directory
,W/ResourcesManager( 7543): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1551): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7567 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@9952b68
,I/GCoreNlp( 1753): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  878): Killing 7304:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/EmailService.MarketingOptInSetter( 2631): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7304/cgroup.procs: No such file or directory
,I/ContactLocale( 7567): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/GetNotificationsWS( 2631): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2631): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2631): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2631): onServiceConnected()
D/GetNotificationsWS( 2631): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2631): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  878): Killing 7417:com.google.android.talk/u0a70 (adj 15): empty #7
,I/PushService( 2631): started with background data enabled, making sure notification mechanism is enabled
,I/Launcher( 1569): Deferring update until onResume
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7417/cgroup.procs: No such file or directory
,I/art     (  878): Explicit concurrent mark sweep GC freed 17652(866KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.766ms total 120.935ms
,D/WearableService( 1753): callingUid 10016, callindPid: 1753
,D/LocationInitializer( 6315): Restart initialization of location
,E/MDM     ( 1753): [171] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1753): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2631): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2631): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2631): [debug] > In cancelAnyPendingIntentSetPreviously
,W/GCoreFlp( 1753): No location to return for getLastLocation()
,W/FusedLocationProvider( 1753): location=null
,I/ActivityManager(  878): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2631): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2631): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2631): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7604 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2631): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2631): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2631): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2631): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2631): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2631): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2631): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2631): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2631): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1417): onFinishInput()
,W/IInputConnectionWrapper( 6473): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7604): Register our PhoneStateListener
,I/LaunchCheckinHandler(  878): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,165
,V/SetupWizard( 7604): Connected to Gservices successfully
,D/GCM     ( 1753): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7624 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7651 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7452:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_7452/cgroup.procs: No such file or directory
,W/ResourcesManager( 7651): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7651): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7651): MmsConfig.loadMmsSettings
I/Babel_SMS( 7651): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7651): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7651): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7651): MmsConfig.loadFromResources
,E/Babel_SMS( 7651): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7651): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7651): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7651): startup - clean
,I/Babel   ( 7651): deleted: false for 0
,D/GCM     ( 1753): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7651): Unsupported mime audio/amr-wb-plus
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7683 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/VideoCapabilities( 7651): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7651): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  878): Killing 7524:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_7524/cgroup.procs: No such file or directory
,I/vclib   ( 7651): onServiceConnected
,W/Babel   ( 7651): Attempted to change video mute state without an active call.
,I/art     ( 6263): Explicit concurrent mark sweep GC freed 3075(133KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 338us total 24.041ms
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7710 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7729 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7543:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7543/cgroup.procs: No such file or directory
,W/asset   ( 7729): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7729): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7729): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7729): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7651): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7651): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7651): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PackageBroadcastService( 6315): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@372b5333 new=com.google.android.velvet.VelvetApplication@372b5333
,I/UpdateIcingCorporaServi( 7683): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6315): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7760 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 7651): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7651): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 6315): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7760): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7683): UpdateCorporaTask done [took 178 ms] updated apps [took 178 ms] 
,I/ActivityManager(  878): Killing 7624:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7624/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7798 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.766ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.770ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.361ms
,I/ActivityManager(  878): Killing 7604:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7604/cgroup.procs: No such file or directory
,D/Finsky  ( 7798): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7798): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7798): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7798): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7798): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7798): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7798): Skipping gmscore version check
,I/ActivityManager(  878): Killing 7710:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_7710/cgroup.procs: No such file or directory
,D/Finsky  ( 7798): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7798): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/TaskPersister(  878): removeObsoleteFile: deleting file=5_task.xml
,I/Icing   ( 6315): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6315): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6315): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  878): Killing 7729:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_7729/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Killing 7651:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7651/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 6315): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311100, SEQNUM=4504, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-365, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2485): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  878): send {364cd4b2, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {1b373288, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  878): send {202bfde1, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  878): done {1b373288, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,V/AlarmManager(  878): done {202bfde1, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [31ms]
,V/AlarmManager(  878): done {364cd4b2, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/CheckinService( 6315): Checkin interval check for package: unspecified last checkin: 1453190840180 min interval config: 0 actual interval: 44977
,I/CheckinService( 6315): Checking schedule, now: 1453190885167 next: 1453190870067
I/CheckinService( 6315): active receiver: enabled
,I/CheckinService( 6315): Preparing to send checkin request
I/EventLogService( 6315): Accumulating logs since 1453190835692
,I/CheckinRequestBuilder( 6315): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6315): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  878): Explicit concurrent mark sweep GC freed 15712(798KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.862ms total 113.415ms
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7862 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7862): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7862): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7862): VM with version 2.1.0 has multidex support
,I/MultiDex( 7862): install
I/MultiDex( 7862): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7862): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7862): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7862): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c5b8f5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7862): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1753): callingUid 10016, callindPid: 1753
,E/MDM     ( 1753): [208] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6315): Restart initialization of location
,D/AuthorizationBluetoothService( 1753): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1753): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 7862): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7862): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/GCoreFlp( 1753): No location to return for getLastLocation()
,W/FusedLocationProvider( 1753): location=null
,D/NativeLibraryUtils( 7862): Install completed successfully. count=14 extracted=0
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
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
,D/QSEECOMAPI: (  307): Loaded image: APP id = 3
,D/DrmWidevineDash(  307): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
E/DrmWidevineDash(  307): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  307): hlos api version =  9
,D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  307): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  307): OEMCrypto_OpenSession: starts! SID=0xae21d960
,D/DrmWidevineDash(  307): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  307): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: starts! randomData=0xb877f2c8, dataLength=8
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb886bae0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  307): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  307): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  307): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  307): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: starts! deviceID=0xb88b8a08, idLength=0xb5558730
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: starts!
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
,D/WVCdm   (  307): PrepareKeyRequest: nonce=2907301366
D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb87727b8
D/DrmWidevineDash(  307): message_length=1591, signature=0xb886c010, signature_length=3042281236
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  307): CdmEngine::CloseSession
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  307): L3 Terminate.
D/DrmWidevineDash(  307): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  307): Service_Uninitialize: starts!
D/QSEECOMAPI: (  307): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  307): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  307): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7906): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7906): dex2oat took 92.748ms (threads: 4)
,I/Adreno-EGL( 7862): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7862): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7862): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7862): Local Branch: 
I/Adreno-EGL( 7862): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7862): Local Patches: NONE
I/Adreno-EGL( 7862): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7862): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7862): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7862): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7862): Local Branch: 
I/Adreno-EGL( 7862): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7862): Local Patches: NONE
I/Adreno-EGL( 7862): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  307): CdmEngine::OpenSession
I/WVCdm   (  307): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  307): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  307): Service_Initialize: starts!
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  307): App is not loaded in QSEE
E/QSEECOMAPI: (  307): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
,E/QSEECOMAPI: (  307): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  307): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  307): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  307): App is not loaded in QSEE
,D/QSEECOMAPI: (  307): Loaded image: APP id = 3
,D/DrmWidevineDash(  307): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
E/DrmWidevineDash(  307): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  307): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  307): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  307): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  307): OEMCrypto_OpenSession: starts! SID=0xbecd84e0
,D/DrmWidevineDash(  307): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  307): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  307): OEMCrypto_GetRandom: starts! randomData=0xb886b8e0, dataLength=8
D/DrmWidevineDash(  307): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb87805b0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  307): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  307): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  307): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  307): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  307): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: starts! deviceID=0xb88b8a28, idLength=0xb5558730
,D/DrmWidevineDash(  307): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  307): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  307): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  307): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  307): hlos api version =  9
D/DrmWidevineDash(  307): tz api version =  8
D/DrmWidevineDash(  307): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  307): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  307): PrepareKeyRequest: nonce=3930951627
D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb87728e8
D/DrmWidevineDash(  307): message_length=1626, signature=0xb876b330, signature_length=3042281236
,D/DrmWidevineDash(  307): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  307): CdmEngine::CloseSession
D/DrmWidevineDash(  307): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  307): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  307): L3 Terminate.
,D/DrmWidevineDash(  307): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  307): Service_Uninitialize: starts!
D/QSEECOMAPI: (  307): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  307): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  307): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  307): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7862): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7862): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7862): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7862): Local Branch: 
I/Adreno-EGL( 7862): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7862): Local Patches: NONE
I/Adreno-EGL( 7862): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7862): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7862): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7862): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7862): Local Branch: 
I/Adreno-EGL( 7862): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7862): Local Patches: NONE
I/Adreno-EGL( 7862): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6315): Classify the device as Phone.
,I/CheckinTask( 6315): Sending checkin request (9445 bytes)
,I/CheckinRequestBuilder( 6315): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6315): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6315): Classify the device as Phone.
,I/CheckinTask( 6315): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6315): Checking schedule, now: 1453190890402 next: 1453792027397
I/CheckinService( 6315): active receiver: disabled
,D/CheckinService( 6315): Recording last checkin time for package unspecified as 1453190890422
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7932 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7932): Register our PhoneStateListener
,V/SetupWizard( 7932): Connected to Gservices successfully
,D/GCM     ( 1753): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Killing 7567:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  878): Killing 7683:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7567/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_7683/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7958 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3c5d7fbb
,I/GCoreNlp( 1753): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1569): Deferring update until onResume
,I/art     ( 1753): Explicit concurrent mark sweep GC freed 104533(5MB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 15MB/25MB, paused 1.040ms total 117.043ms
,E/DataBuffer( 1753): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a32a18b)
,E/DataBuffer( 1753): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21495268)
E/DataBuffer( 1753): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27c3f681)
,E/DataBuffer( 1753): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c517326)
E/DataBuffer( 1753): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@527cb67)
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7995 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8012 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7760:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  878): Killing 7798:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7760/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_7798/cgroup.procs: No such file or directory
,W/ResourcesManager( 8012): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8012): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8012): MmsConfig.loadMmsSettings
I/Babel_SMS( 8012): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8012): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8012): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8012): MmsConfig.loadFromResources
,E/Babel_SMS( 8012): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8012): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8012): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8012): startup - clean
,I/Babel   ( 8012): deleted: false for 0
,I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8045 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8012): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8012): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 8012): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8012): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8012): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8012): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8012): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8012): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8070 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 7932:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8045): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7932/cgroup.procs: No such file or directory
,I/vclib   ( 8012): onServiceConnected
,W/Babel   ( 8012): Attempted to change video mute state without an active call.
,W/asset   ( 8070): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8070): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 8070): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8070): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
W/ResourcesManager( 8012): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8012): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6315): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6315): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7958): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6315): updateResources: need to parse f{com.google.android.gms}
,V/JNIHelp ( 8012): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8012): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8012): Installed default security provider GmsCore_OpenSSL
,I/art     (  878): Explicit concurrent mark sweep GC freed 17899(937KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.670ms total 122.028ms
,I/UpdateIcingCorporaServi( 7958): UpdateCorporaTask done [took 131 ms] updated apps [took 131 ms] 
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@372b5333 new=com.google.android.velvet.VelvetApplication@372b5333
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8100 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8100): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8128 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7862:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_7862/cgroup.procs: No such file or directory
,D/Finsky  ( 8128): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8128): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8128): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8128): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 8128): Skipping gmscore version check
,D/Finsky  ( 8128): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8128): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  878): Killing 7995:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_7995/cgroup.procs: No such file or directory
,D/Finsky  ( 8128): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8128): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6315): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6315): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  878): Killing 8070:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_8070/cgroup.procs: No such file or directory
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  878): Killing 8012:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_8012/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1417): run()
,I/Keyboard.Facilitator( 1417): flushDynamicLanguageModels()
,I/ConfigService( 1753): onCreate
,I/ConfigService( 1753): onDestroy
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ClearcutLoggerApiImpl( 1753): disconnect managed GoogleApiClient
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310668, SEQNUM=4528, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-474, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2485): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2485): Disconnected process message: 10, size: 0
,I/jxcore-log( 6473): --= Surplus to requirements =--
I/jxcore-log( 6473): 
I/jxcore-log( 6473): ****TEST TOOK:  ms ****
I/jxcore-log( 6473): 
I/jxcore-log( 6473): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6473): 
,D/AndroidRuntime( 8203): 
D/AndroidRuntime( 8203): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8203): CheckJNI is OFF
,D/AndroidRuntime( 8203): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  878): Force stopping com.test.thalitest appid=10464 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 6473:com.test.thalitest/u0a464 (adj 9): stop com.test.thalitest
,W/PackageSettings(  878): Skipping PackageSetting{3e29a70e com.example.hello/10440} due to missing metadata
,I/WindowState(  878): WIN DEATH: Window{1edd8568 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  878): Client connection lost with reason: 4
,I/ActivityManager(  878):   Force finishing activity ActivityRecord{2bc9efdd u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  878): Spurious death for ProcessRecord{2b6ba162 6473:com.test.thalitest/u0a464}, curProc for 6473: null
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10464 user=0: pkg removed
,I/ActivityManager(  878):   Force finishing activity ActivityRecord{2bc9efdd u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  878): Duplicate finish request for ActivityRecord{2bc9efdd u0 com.test.thalitest/.MainActivity t6 f}
,I/art     ( 3027): Explicit concurrent mark sweep GC freed 10125(2MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 7MB/12MB, paused 816us total 38.823ms
,W/GeofencerStateMachine( 1753): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
,I/Decoder ( 1417): createOrResetDecoder
,D/VoicemailCleanupService( 8045): Cleaning up data for package: com.test.thalitest
,I/art     ( 1569): Explicit concurrent mark sweep GC freed 5037(310KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 498us total 105.574ms
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8231 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  878): Explicit concurrent mark sweep GC freed 15563(1004KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.156ms total 166.150ms
,I/ConfigService( 1753): onCreate
,I/art     (  878): WaitForGcToComplete blocked for 57.360ms for cause Explicit
,W/asset   ( 8231): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8231): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8231): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8231): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = user
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1417): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1417): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1417): run()
I/StatsUtilsManager( 1417): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1417): shouldRecordStats() = Too Soon
,I/ActivityManager(  878): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8256 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  878): removeObsoleteFile: deleting file=6_task.xml
,I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.347ms
,I/ActivityManager(  878): Killing 7958:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Launcher( 1569): Deferring update until onResume
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 22.849ms
,I/art     (  878): Explicit concurrent mark sweep GC freed 4586(233KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.349ms total 201.481ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.929ms
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_7958/cgroup.procs: No such file or directory
,D/AndroidRuntime( 8203): Shutting down VM
,W/ContextImpl( 8256): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6315): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6315): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6315): Reading stored module config
,D/ChimeraCfgMgr( 6315): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6315): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 6315): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6315): App measurement is starting up, version: 8489
,I/GMPM-SVC( 6315): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1753): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1753): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/FileUtils( 6315): Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,D/gH_CompatibleDatabase( 6315): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6315): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 6315): (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
,D/gH_CompatibleDatabase( 6315): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,--------- beginning of crash
E/AndroidRuntime( 6315): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6315): Process: com.google.android.gms, PID: 6315
E/AndroidRuntime( 6315): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6315): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6315): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 6315): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6315): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6315): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 6315): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6315): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6315): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6315): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6315): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8287 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Process ( 6315): Sending signal. PID: 6315 SIG: 9
,E/DropBoxManagerService(  878): Can't write: system_app_crash
E/DropBoxManagerService(  878): java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  878): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  878): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  878): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  878): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  878): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  878): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  878): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  878): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  878): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  878): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  878): 	... 5 more
,D/WifiService(  878): Client connection lost with reason: 4
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
