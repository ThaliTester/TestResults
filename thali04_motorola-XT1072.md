#### Test 561510938d3c4f5_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/AndroidRuntime( 6367): 
D/AndroidRuntime( 6367): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6367): CheckJNI is OFF
D/AndroidRuntime( 6367): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6385 uid=10451 gids={50451, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6367): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6385): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6385): Time to load native libraries: 3 ms (timestamps 7540-7543)
I/LibraryLoader( 6385): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6385): Binding Chromium to main looper Looper (main, tid 1) {2ba237b2}
,I/LibraryLoader( 6385): Expected native library version number "",actual native library version number ""
,I/chromium( 6385): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6385): Initializing chromium process, singleProcess=true
W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6385): ApplicationContext is null in ApplicationStatus
,W/chromium( 6385): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6385): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6385): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6385): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6385): Local Branch: 
I/Adreno-EGL( 6385): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6385): Local Patches: NONE
I/Adreno-EGL( 6385): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20862861:true
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{22133862 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6385): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6385): CordovaWebView is running on device made by: motorola
,W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6385): Render dirty regions requested: true
D/Atlas   ( 6385): Validating map...
W/chromium( 6385): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6385): Initialized EGL, version 1.4
D/OpenGLRenderer( 6385): Enabling debug mode 0
I/Keyboard.Facilitator( 1410): onFinishInput()
I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,944
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +874ms (total +944ms)
W/IInputConnectionWrapper( 6385): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6385): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6385): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6385): Cannot call determinedVisibility() - never saw a connection for the pid: 6385
D/JsMessageQueue( 6385): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6385): JniHelper::setJavaVM(0xb89cf310), pthread_self() = -1193928888
D/JX-Cordova( 6385): jxcore cordova android initializing
,W/jxcore-log( 6385): Initializing JXcore engine
W/jxcore-log( 6385): JXcore engine is ready
,W/jxcore-log( 6385): Starting JXcore engine
,W/.test.thalitest( 6385): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10451 path="socket:[9564]" dev="sockfs" ino=9564 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6385): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10451 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6385): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10451 path="socket:[7464]" dev="sockfs" ino=7464 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6385): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10451 path="socket:[29539]" dev="sockfs" ino=29539 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6385): Platform android
W/jxcore-log( 6385): 
W/jxcore-log( 6385): Process ARCH arm
W/jxcore-log( 6385): 
,I/jxcore-log( 6385): JXcore Cordova bridge is ready!
I/jxcore-log( 6385): 
,W/jxcore-log( 6385): JXcore engine is started
,I/chromium( 6385): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6385): Toggling radios to true
I/jxcore-log( 6385): 
,D/BluetoothAdapter( 6385): enable(): BT is already enabled..!
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: true pid=6385, uid=10451
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6385): Radios toggled
I/jxcore-log( 6385): 
I/jxcore-log( 6385): My device name is: motorola-XT1072
I/jxcore-log( 6385): 
,I/wpa_supplicant( 1431): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  308): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  308):  STA Disconnected !!
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): get_property_value, Enter
I/MDMCTBK (  308): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  308): get_property_value, Exit
I/MDMCTBK (  308): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  308): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  308): set_property_value, Enter
I/MDMCTBK (  308): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  308): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  308): set_property_value, Exit
I/MDMCTBK (  308): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  308): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  308): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  308): set_property_value, Enter
I/MDMCTBK (  308): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  308): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  308): set_property_value, Exit
E/MDMCTBK (  308): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
D/TCMD    (  482): NL - Read 68 bytes from update socket.
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
D/TCMD    (  482): NL - message type is RTM_NEWLINK
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
I/wpa_supplicant( 1431): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  308): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  883): InitialState.processMessage what=4
,I/wpa_supplicant( 1431): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  308): Event received = CTRL-EVENT-REGDOM-CHANGE
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/Tethering(  883):  0
,D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1431): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  306): Clearing all IP addresses on wlan0
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 21
D/TCMD    (  482): Listening for incoming client connection request
,V/NativeCrypto( 1739): Read error: ssl=0xb8c97758: I/O error during system call, Connection timed out
,V/NativeCrypto( 1739): SSL shutdown failed: ssl=0xb8c97758: I/O error during system call, Broken pipe
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
,D/WifiMetrics(  883): connected time updated 122242
,D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6459 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1431): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  883): Start Disconnecting Watchdog 1
D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/wpa_supplicant( 1431): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  308): Event received = CTRL-EVENT-SCAN-STARTED 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
E/WifiStateMachine(  883): ConnectModeState: Network connection lost 
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1431): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CommandListener(  306): Clearing all IP addresses on wlan0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,W/ResourcesManager( 6459): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  883): Explicit concurrent mark sweep GC freed 53997(2MB) AllocSpace objects, 3(235KB) LOS objects, 33% free, 20MB/30MB, paused 1.622ms total 126.585ms
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6485 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6153:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  308): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  308): Event received = WPS-AP-AVAILABLE 
,D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/WifiStateMachine(  883): [1,452,860,502,866 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1431): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  308): Event received = Trying to associate with
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1431): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@201df846 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  883): setDetailed state send new extra info0x
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_6153/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6485): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  482): NL - Read 312 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 192 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/wpa_supplicant( 1431): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  308): Event received = Associated with c0:ff:d4
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/Tethering(  883): ApnList is empty for checkDunConfigured()
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1431): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1431): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  308): Event received = WPA: Key negotiation com
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  308): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  308):  STA Connected !!
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/MDMCTBK (  308): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  308): get_freq !!, resp=2412
I/MDMCTBK (  308): get_freq !!, Strip data
I/MDMCTBK (  308): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): get_property_value, Enter
I/MDMCTBK (  308): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  308): get_property_value, Exit
I/MDMCTBK (  308): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
,I/MDMCTBK (  308): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  308): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  308): set_property_value, Enter
,I/MDMCTBK (  308): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  308): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  308): set_property_value, Exit
I/MDMCTBK (  308): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  308): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  308): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): get_property_value, Enter
I/MDMCTBK (  308): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  308): get_property_value, Exit
I/MDMCTBK (  308): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195320056
I/MDMCTBK (  308): return from set_get_from_wpa_supplicant
I/MDMCTBK (  308): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  308): set_property_value, Enter
I/MDMCTBK (  308): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  308): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  308): set_property_value, Exit
E/MDMCTBK (  308): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  308): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  308): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  308): , reply_len: 3, ret: 0
E/MDMCTBK (  308): MdmCutbackHndler, resp=OK
E/MDMCTBK (  308): 
D/MDMCTBK (  308): wifi_set_tx_pwr: Exit
,D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  306): Setting iface cfg
,E/WifiStateMachine(  883): Start Dhcp Watchdog 2
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/wpa_supplicant( 1431): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1431): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d7925b5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d7925b5 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6485): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6485): MmsConfig.loadMmsSettings
I/Babel_SMS( 6485): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6485): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6485): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6485): MmsConfig.loadFromResources
,E/Babel_SMS( 6485): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6485): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,E/DHCPCD  ( 6529): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6529): version 5.5.6 starting
E/DHCPCD  ( 6529): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6529): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6529): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/Settings( 6485): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6485): startup - clean
,I/Babel   ( 6485): deleted: false for 0
,D/DHCPCD  ( 6529): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6529): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6529): wlan0: sending REQUEST (xid 0x6f3d3507), next in 4.45 seconds
,W/VideoCapabilities( 6485): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6485): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 6485): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6485): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6485): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6485): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6485): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6485): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 6184:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6184/cgroup.procs: No such file or directory
,I/vclib   ( 6485): onServiceConnected
,W/Babel   ( 6485): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6529): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6529): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6529): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6529): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6529): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6529): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 20
D/TCMD    (  482): Listening for incoming client connection request
,D/DHCPCD  ( 6529): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/global frequency( 2562): no tags to log
D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 56017(3MB) AllocSpace objects, 36(1245KB) LOS objects, 40% free, 7MB/12MB, paused 987us total 48.405ms
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend true
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): WifiStateMachine DHCP successful
E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  883): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  883): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  883): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883):    accepting network in place of null
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 4265(178KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 577us total 26.616ms
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2562): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2562): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2562): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2562): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2562): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  883): send {2044dca5, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {2044dca5, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1459): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6597 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1459): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/Central_PollingManager( 1459): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2562): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2562): [debug] > CusSM.onRadioDown
,I/MusicStore( 6597): Database version: 120
,I/art     (  883): Explicit concurrent mark sweep GC freed 27867(1360KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.977ms total 120.273ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6597): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6597): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6597): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6597): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6597): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6597): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
W/ActivityThread( 6597): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6597): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e89cc6e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6597): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6597): GMSCore installation verified
I/ConfigStore( 6597): Config Database version: 1
,I/MediaRouter( 6597): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6597): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6597): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6597): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6638 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.311ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 18.877ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.897ms
,I/GHttpClientFactory( 6597): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6597): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 6010:android.process.acore/u0a7 (adj 15): empty #7
,V/Mms     ( 6638): mnc/mcc: 
V/Mms     ( 6638): tag: int value: recipientLimit - 20
,V/Mms     ( 6638): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6638): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6638): tag: int value: maxSubjectLength - 80
V/Mms     ( 6638): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6638): tag: bool value: enableGroupMms - false
V/Mms     ( 6638):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6010/cgroup.procs: No such file or directory
,W/ResourcesManager( 6638): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6670 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6091:com.android.vending/u0a32 (adj 15): empty #7
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,D/PhoneMonitor( 6670): Register our PhoneStateListener
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_6091/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6670): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6670): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 6485:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6485/cgroup.procs: No such file or directory
,I/CheckinService( 6245): Checkin interval check for package: unspecified last checkin: 1452860424804 min interval config: 0 actual interval: 82424
,I/CheckinService( 6245): Disabling old GoogleServicesFramework version
,I/CheckinService( 6245): Checking schedule, now: 1452860507254 next: 1452860454789
I/CheckinService( 6245): active receiver: enabled
,I/CheckinService( 6245): Preparing to send checkin request
,I/iu.SyncManager( 6245): SYNC; picasa accounts
,I/EventLogService( 6245): Accumulating logs since 1452860421243
D/NetworkLogImpl( 6245): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6245): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6245): num queued entries: 0
,I/iu.UploadsManager( 6245): num updated entries: 0
,I/iu.SyncManager( 6245): NEXT; no task
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6702 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6245): Checkin reason type: 8 attempt count: 1
,D/WifiService(  883): New client listening to asynchronous messages
,E/ActivityThread( 6245): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6728 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/chromium( 6385): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6745 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6745): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6728): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6728): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6728): VM with version 2.1.0 has multidex support
I/MultiDex( 6728): install
I/MultiDex( 6728): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6728): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6728): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6728): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21ab7e37: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6728): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  883): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1459): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): now: 197807 ,futureTime: 9223372036854775807
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2562): now: 197808 ,futureTime: 9223372036854775807
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): now: 197808 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1459): now: 197809 ,futureTime: 86474435
D/Central_PollingManager( 1459): Polling alarm set to expire at: 86474435 Current Time: 197809
,D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6597): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2562): [debug] > PollingManagerService, now: 197814 ,futureTime: 20550114
D/OtaApp  ( 2562): [debug] > Polling alarm set to expire at: 20550114 Current Time: 197815
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2562): Not proxy app, so login/provision not allowed
,I/art     ( 6728): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6728): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 6745): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6745): MmsConfig.loadMmsSettings
I/Babel_SMS( 6745): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6745): MmsConfig.loadFromDatabase
,I/art     ( 2562): Explicit concurrent mark sweep GC freed 21433(1204KB) AllocSpace objects, 2(55KB) LOS objects, 40% free, 11MB/19MB, paused 1.467ms total 81.253ms
,E/Babel_SMS( 6745): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6745): MmsConfig.loadFromResources
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,E/Babel_SMS( 6745): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6745): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,D/NativeLibraryUtils( 6728): Install completed successfully. count=14 extracted=0
,I/art     (  883): Explicit concurrent mark sweep GC freed 11259(544KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.718ms total 120.775ms
,D/MMApiProvisionService( 2562): set mOutstandingReq to true.
I/ Nonce  ( 2562):  Nonce getNonce 
I/ Nonce  ( 2562):  Nonce Request 
I/ Nonce  ( 2562):  Nonce execute Request 
,D/MMApiWebService( 2562): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/WVCdm   (  310): Instantiating CDM.
,I/WVCdm   (  310): CdmEngine::OpenSession
I/WVCdm   (  310): Level3 Library Sep 25 2014 17:10:03
D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
W/WVCdm   (  310): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2562): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2562): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/Settings( 6745): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DrmWidevineDash(  310): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  310): Service_Initialize: starts!
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
I/Babel_Crash( 6745): startup - clean
D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2562): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/QSEECOMAPI: (  310): Loaded image: APP id = 3
,D/DrmWidevineDash(  310): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe5000
E/DrmWidevineDash(  310): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe5000
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  310): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: starts! SID=0xbef414e0
D/DrmWidevineDash(  310): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: starts! randomData=0xb7bd2aa8, dataLength=8
I/Babel   ( 6745): deleted: false for 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7bbb518, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  310): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  310): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  310): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  310): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c06dd0, idLength=0xb54c0730
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  310): PrepareKeyRequest: nonce=2328552593
D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7ad45d0
D/DrmWidevineDash(  310): message_length=1591, signature=0xb7b33d20, signature_length=3041658644
,D/MMApiWebService( 2562): generating token using payload instead of using session token
,D/ Nonce  ( 2562):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6784 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MMApiWSBase( 2562): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,W/VideoCapabilities( 6745): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6745): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6745): Unsupported mime video/mpeg2
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  310): CdmEngine::CloseSession
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  310): L3 Terminate.
D/DrmWidevineDash(  310): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  310): Service_Uninitialize: starts!
D/QSEECOMAPI: (  310): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  310): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  310): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_Terminate: ends! returns 0
,I/VideoCapabilities( 6745): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6745): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6745): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6745): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6745): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6745): onServiceConnected
,W/Babel   ( 6745): Attempted to change video mute state without an active call.
,I/WVCdm   (  310): CdmEngine::OpenSession
I/WVCdm   (  310): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  310): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  310): Service_Initialize: starts!
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
,I/Babel   ( 6745): connection state changed from UNKNOWN to CONNECTED
,D/QSEECOMAPI: (  310): Loaded image: APP id = 3
,I/ActivityManager(  883): Killing 6459:com.motorola.context/u0a8 (adj 15): empty #7
D/DrmWidevineDash(  310): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe5000
E/DrmWidevineDash(  310): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe5000
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  310): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: starts! SID=0xbef414e0
D/DrmWidevineDash(  310): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: starts! randomData=0xb7ab4a80, dataLength=8
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7bbb518, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  310): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  310): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  310): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  310): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c06e10, idLength=0xb55c0730
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  310): PrepareKeyRequest: nonce=530126262
D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7bbb518
D/DrmWidevineDash(  310): message_length=1626, signature=0xb7b2e040, signature_length=3042707220
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_6459/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  310): CdmEngine::CloseSession
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  310): L3 Terminate.
D/DrmWidevineDash(  310): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  310): Service_Uninitialize: starts!
D/QSEECOMAPI: (  310): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  310): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  310): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_Terminate: ends! returns 0
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6784): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6784): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6784): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6784): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6784): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6784):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6784):   adb logcat -s GAv4
,W/GAv4    ( 6784): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6784): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6784): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6821): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6821): dex2oat took 92.654ms (threads: 4)
,I/Adreno-EGL( 6728): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6728): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6728): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6728): Local Branch: 
I/Adreno-EGL( 6728): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6728): Local Patches: NONE
I/Adreno-EGL( 6728): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 6784): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Adreno-EGL( 6728): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6728): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6728): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6728): Local Branch: 
I/Adreno-EGL( 6728): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6728): Local Patches: NONE
I/Adreno-EGL( 6728): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/LibraryLoader( 6784): Time to load native libraries: 1 ms (timestamps 9202-9203)
I/LibraryLoader( 6784): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6784): Binding Chromium to main looper Looper (main, tid 1) {21a26327}
,I/LibraryLoader( 6784): Expected native library version number "",actual native library version number ""
I/chromium( 6784): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6784): Initializing chromium process, singleProcess=true
,W/art     ( 6784): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6784): ApplicationContext is null in ApplicationStatus
,W/chromium( 6784): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6784): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6784): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6784): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6784): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6784): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6784): Local Branch: 
I/Adreno-EGL( 6784): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6784): Local Patches: NONE
I/Adreno-EGL( 6784): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/ Nonce  ( 2562):  Nonce Reponse 
D/        ( 2562): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"7352a128-5169-4239-b47e-5bf85fff4ae1"}
D/MMApiWSBase( 2562): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2562):  Nonce Handle Reponse 
D/MMApiProvisionService( 2562): mOutstandingReq set to false
,W/AudioManagerAndroid( 6784): Requires BLUETOOTH permission
,I/NSApplication( 6784): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6859 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6597:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 3734(162KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 791us total 36.497ms
,D/MMApiProvisionService( 2562):  pTime 1452855605507 sExp 172742 cTime 1452860509675 tTime 1453028347507
D/MMApiProvisionService( 2562):  No login Required 
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6597/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6728): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6728): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6728): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6728): Local Branch: 
I/Adreno-EGL( 6728): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6728): Local Patches: NONE
I/Adreno-EGL( 6728): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6728): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6728): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6728): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6728): Local Branch: 
I/Adreno-EGL( 6728): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6728): Local Patches: NONE
I/Adreno-EGL( 6728): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6245): Classify the device as Phone.
,W/DataUsage( 2562): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6892 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6638:com.android.mms/u0a23 (adj 15): empty #7
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 12:21:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452860510100], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452860510080]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_6638/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1534): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): Inetcondition changed, white->blue
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6914 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6935 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6702:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/CheckinTask( 6245): Sending checkin request (9579 bytes)
,I/ContactLocale( 6914): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 6670:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_6702/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_6670/cgroup.procs: No such file or directory
,I/MusicStore( 6935): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6935): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6935): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6935): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6935): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6935): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6935): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6935): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6935): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e89cc6e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6935): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6935): GMSCore installation verified
,I/ConfigStore( 6935): Config Database version: 1
,I/MediaRouter( 6935): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6935): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6935): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6935): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6982 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6245): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6245): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6216): Explicit concurrent mark sweep GC freed 1530(65KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 401us total 56.850ms
,I/GHttpClientFactory( 6935): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  883): Explicit concurrent mark sweep GC freed 9882(487KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.536ms total 110.909ms
,I/GoogleURLConnFactory( 6935): Using platform SSLCertificateSocketFactory
,V/Mms     ( 6982): mnc/mcc: 
,V/Mms     ( 6982): tag: int value: recipientLimit - 20
V/Mms     ( 6982): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6982): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6982): tag: int value: maxSubjectLength - 80
V/Mms     ( 6982): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6982): tag: bool value: enableGroupMms - false
,V/Mms     ( 6982):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  883): Killing 6745:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6745/cgroup.procs: No such file or directory
,W/ResourcesManager( 6982): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7018 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 24.745ms
,I/ActivityManager(  883): Killing 6784:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 22.034ms
,D/PhoneMonitor( 7018): Register our PhoneStateListener
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.650ms
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_6784/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7018): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7018): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 6859:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_6859/cgroup.procs: No such file or directory
,I/CheckinService( 6245): Checkin interval check for package: unspecified last checkin: 1452860424804 min interval config: 0 actual interval: 86966
,I/CheckinRequestBuilder( 6245): Classify the device as Phone.
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7038 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinTask( 6245): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6245): Checking schedule, now: 1452860511860 next: 1453461648845
I/CheckinService( 6245): active receiver: disabled
,I/CheckinService( 6245): Checking schedule, now: 1452860511881 next: 1453461648845
I/CheckinService( 6245): active receiver: disabled
,D/CheckinService( 6245): Recording last checkin time for package unspecified as 1452860511884
,I/ActivityManager(  883): Killing 6914:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  883): Killing 6892:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6914/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6892/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7059 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6935:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6935/cgroup.procs: No such file or directory
,W/ResourcesManager( 7059): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7059): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7059): MmsConfig.loadMmsSettings
I/Babel_SMS( 7059): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7059): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7059): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7059): MmsConfig.loadFromResources
,E/Babel_SMS( 7059): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7059): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7059): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7059): startup - clean
,I/Babel   ( 7059): deleted: false for 0
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310373, SEQNUM=4448, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-257, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7097 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,W/VideoCapabilities( 7059): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7059): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7059): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7059): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7059): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7059): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7059): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7059): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7059): onServiceConnected
,W/Babel   ( 7059): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7097): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7097): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7097): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7097):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7097):   adb logcat -s GAv4
,I/Babel   ( 7059): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 6982:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7097): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7097): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_6982/cgroup.procs: No such file or directory
,W/GAv4    ( 7097): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7097): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7097): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7097): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7097): Time to load native libraries: 2 ms (timestamps 2940-2942)
,I/LibraryLoader( 7097): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7097): Binding Chromium to main looper Looper (main, tid 1) {21a26327}
,I/LibraryLoader( 7097): Expected native library version number "",actual native library version number ""
I/chromium( 7097): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7097): Initializing chromium process, singleProcess=true
,W/art     ( 7097): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7097): ApplicationContext is null in ApplicationStatus
,W/chromium( 7097): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7097): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7097): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7097): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7097): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7097): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7097): Local Branch: 
I/Adreno-EGL( 7097): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7097): Local Patches: NONE
I/Adreno-EGL( 7097): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7097): Requires BLUETOOTH permission
,I/NSApplication( 7097): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7165 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7018:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7018/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7184 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7038:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
,I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7038/cgroup.procs: No such file or directory
,W/ResourcesManager( 7184): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7204 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7097:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7204): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7059:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7097/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7059/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2562): onServiceConnected()
D/GetNotificationsWS( 2562): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2562): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7241 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2562): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1739): callingUid 10016, callindPid: 1739
,E/MDM     ( 1739): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1739): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6245): Restart initialization of location
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7268 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1739): No location to return for getLastLocation()
W/FusedLocationProvider( 1739): location=null
,I/MusicStore( 7268): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7268): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7268): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7268): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     (  883): Explicit concurrent mark sweep GC freed 13341(683KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.476ms total 111.406ms
,W/ResourcesManager( 7268): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7268): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7268): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7268): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7268): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e89cc6e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7268): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7268): GMSCore installation verified
,I/ConfigStore( 7268): Config Database version: 1
,I/MediaRouter( 7268): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7268): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7268): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7268): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7300 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7268): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7268): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 7165:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     ( 1739): Explicit concurrent mark sweep GC freed 109664(6MB) AllocSpace objects, 29(487KB) LOS objects, 40% free, 15MB/25MB, paused 1.130ms total 120.474ms
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7165/cgroup.procs: No such file or directory
,V/Mms     ( 7300): mnc/mcc: 
,V/Mms     ( 7300): tag: int value: recipientLimit - 20
V/Mms     ( 7300): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7300): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7300): tag: int value: maxSubjectLength - 80
V/Mms     ( 7300): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7300): tag: bool value: enableGroupMms - false
,V/Mms     ( 7300):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,E/DataBuffer( 1739): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@243f8ae4)
,E/DataBuffer( 1739): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1bb7cb4d)
E/DataBuffer( 1739): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17c13602)
,E/DataBuffer( 1739): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@344cb13)
E/DataBuffer( 1739): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3ddc7150)
,W/ResourcesManager( 7300): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7331 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7184:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7184/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7331): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7331): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7331): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 7204:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7204/cgroup.procs: No such file or directory
,I/CheckinService( 6245): Checkin interval check for package: unspecified last checkin: 1452860511884 min interval config: 0 actual interval: 3790
,I/CheckinService( 6245): Checkin interval check for package: unspecified last checkin: 1452860511884 min interval config: 0 actual interval: 3792
,I/CheckinService( 6245): Checking schedule, now: 1452860515682 next: 1452860541845
I/CheckinService( 6245): active receiver: disabled
,I/CheckinService( 6245): Checking schedule, now: 1452860515694 next: 1452860541845
I/CheckinService( 6245): active receiver: disabled
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7351 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 22.677ms
,W/ResourcesManager( 7351): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.187ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.535ms
,I/Babel_SMS( 7351): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7351): MmsConfig.loadMmsSettings
I/Babel_SMS( 7351): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7351): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7351): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7351): MmsConfig.loadFromResources
,E/Babel_SMS( 7351): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7351): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7351): startup - clean
,I/Babel   ( 7351): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7378 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7351): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7351): Unsupported mime video/mpeg2
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7378): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7378): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7378):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7378):   adb logcat -s GAv4
,W/ContextImpl( 7378): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/VideoCapabilities( 7351): Unsupported profile 4 for video/mp4v-es
,W/GAv4    ( 7378): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7378): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7378): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
,W/GAv4    ( 7378): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/vclib   ( 7351): onServiceConnected
W/Babel   ( 7351): Attempted to change video mute state without an active call.
,W/GAv4    ( 7378): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7351): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 6728:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6728/cgroup.procs: No such file or directory
,I/WebViewFactory( 7378): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7378): Time to load native libraries: 1 ms (timestamps 6450-6451)
,I/LibraryLoader( 7378): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7378): Binding Chromium to main looper Looper (main, tid 1) {21a26327}
,I/LibraryLoader( 7378): Expected native library version number "",actual native library version number ""
I/chromium( 7378): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7378): Initializing chromium process, singleProcess=true
,W/art     ( 7378): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7378): ApplicationContext is null in ApplicationStatus
,W/chromium( 7378): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7378): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7378): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7378): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7378): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7378): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7378): Local Branch: 
I/Adreno-EGL( 7378): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7378): Local Patches: NONE
I/Adreno-EGL( 7378): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,W/AudioManagerAndroid( 7378): Requires BLUETOOTH permission
,I/NSApplication( 7378): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7449 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7268:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7268/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7468 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7300:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7300/cgroup.procs: No such file or directory
,W/ResourcesManager( 7468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7488 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7241:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7488): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7331:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7241/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7331/cgroup.procs: No such file or directory
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,D/GetNotificationsWS( 2562): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 2562): onServiceConnected()
,D/GetNotificationsWS( 2562): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 2562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2562): ServiceHandler.handleMessage: mWaitCount=0
,I/PushService( 2562): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2562): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2562): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2562): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2562): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2562): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7523 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
D/OtaApp  ( 2562): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2562): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/OtaApp  ( 2562): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2562): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2562): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2562): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@77df36a
,W/IInputConnectionWrapper( 6385): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1410): onFinishInput()
,I/GCoreNlp( 1739): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PhoneMonitor( 7523): Register our PhoneStateListener
,I/art     (  883): Explicit concurrent mark sweep GC freed 17734(891KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.283ms total 127.286ms
,I/LaunchCheckinHandler(  883): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,343
,I/Launcher( 1570): Deferring update until onResume
,V/SetupWizard( 7523): Connected to Gservices successfully
,I/ActivityManager(  883): Killing 7351:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7351/cgroup.procs: No such file or directory
,D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7547 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7576 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7378:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7378/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7598 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7615 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7449:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  883): Killing 7468:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7449/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7468/cgroup.procs: No such file or directory
,W/ResourcesManager( 7615): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7615): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7615): MmsConfig.loadMmsSettings
I/Babel_SMS( 7615): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7615): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7615): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7615): MmsConfig.loadFromResources
,E/Babel_SMS( 7615): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7615): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7615): startup - clean
,I/Babel   ( 7615): deleted: false for 0
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7644 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/asset   ( 7644): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7644): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7644): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7644): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7615): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7615): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7615): Unsupported mime video/mpeg2
,D/PackageBroadcastService( 6245): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@26ccc6ac new=com.google.android.velvet.VelvetApplication@26ccc6ac
,I/UpdateIcingCorporaServi( 7576): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6245): Null package name or gms related package.  Ignoreing.
,I/VideoCapabilities( 7615): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7615): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7615): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7615): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7615): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7678 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.421ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 330us total 19.095ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 22.835ms
,I/Icing   ( 6245): updateResources: need to parse f{com.google.android.gms}
,I/vclib   ( 7615): onServiceConnected
W/Babel   ( 7615): Attempted to change video mute state without an active call.
,I/UpdateIcingCorporaServi( 7576): UpdateCorporaTask done [took 179 ms] updated apps [took 179 ms] 
W/ResourcesManager( 7678): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Killing 7547:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/ResourcesManager( 7615): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7615): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7547/cgroup.procs: No such file or directory
,V/JNIHelp ( 7615): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7615): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7615): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7715 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7523:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7523/cgroup.procs: No such file or directory
,D/Finsky  ( 7715): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7715): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7715): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7715): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7715): Skipping gmscore version check
,I/ActivityManager(  883): Killing 7598:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/Finsky  ( 7715): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7715): [1] Libraries$2.run: Finished loading 1 libraries.
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_7598/cgroup.procs: No such file or directory
,D/Finsky  ( 7715): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7715): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task.xml
,I/Icing   ( 6245): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6245): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6245): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 7644:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_7644/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7576:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_7576/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 6245): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312062, SEQNUM=4473, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-309, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1739): disconnect managed GoogleApiClient
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {569c6a0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {184237e7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  883): send {1b80e7a7, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  883): send {24e45f94, *walarm*:com.google.android.apps.plus.checkandengagesync}
,V/AlarmManager(  883): done {569c6a0, *alarm*:android.intent.action.TIME_TICK} [97ms]
,V/AlarmManager(  883): done {184237e7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [100ms]
,V/AlarmManager(  883): done {1b80e7a7, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [106ms]
,I/CheckinService( 6245): Checkin interval check for package: unspecified last checkin: 1452860511884 min interval config: 0 actual interval: 53867
,V/AlarmManager(  883): done {24e45f94, *walarm*:com.google.android.apps.plus.checkandengagesync} [127ms]
,I/CheckinService( 6245): Checking schedule, now: 1452860565773 next: 1452860541845
I/CheckinService( 6245): active receiver: enabled
,I/CheckinService( 6245): Preparing to send checkin request
I/EventLogService( 6245): Accumulating logs since 1452860507466
,I/CheckinRequestBuilder( 6245): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6245): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  883): Explicit concurrent mark sweep GC freed 17176(881KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.905ms total 119.044ms
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7786 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7786): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7786): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7786): VM with version 2.1.0 has multidex support
I/MultiDex( 7786): install
I/MultiDex( 7786): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7786): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7786): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7786): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21ab7e37: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7786): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1739): callingUid 10016, callindPid: 1739
,E/MDM     ( 1739): [210] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1739): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6245): Restart initialization of location
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1739): No location to return for getLastLocation()
,W/FusedLocationProvider( 1739): location=null
,I/art     ( 7786): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7786): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7786): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  310): Instantiating CDM.
,I/WVCdm   (  310): CdmEngine::OpenSession
,I/WVCdm   (  310): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  310): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  310): Service_Initialize: starts!
,D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
,D/QSEECOMAPI: (  310): Loaded image: APP id = 3
,D/DrmWidevineDash(  310): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe5000
,E/DrmWidevineDash(  310): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe5000
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  310): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: starts! SID=0xb12d5960
,D/DrmWidevineDash(  310): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: starts! randomData=0xb7ac1de0, dataLength=8
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7bbb518, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  310): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  310): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  310): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  310): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c06df0, idLength=0xb55c0730
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  310): PrepareKeyRequest: nonce=3929832771
D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7bbb518
D/DrmWidevineDash(  310): message_length=1591, signature=0xb7b2e020, signature_length=3042707220
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  310): CdmEngine::CloseSession
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  310): L3 Terminate.
D/DrmWidevineDash(  310): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  310): Service_Uninitialize: starts!
D/QSEECOMAPI: (  310): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  310): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  310): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  310): CdmEngine::OpenSession
I/WVCdm   (  310): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  310): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  310): Service_Initialize: starts!
,D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
E/QSEECOMAPI: (  310): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  310): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  310): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  310): App is not loaded in QSEE
,D/QSEECOMAPI: (  310): Loaded image: APP id = 3
,D/DrmWidevineDash(  310): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe5000
E/DrmWidevineDash(  310): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe5000
,D/DrmWidevineDash(  310): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  310): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  310): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  310): OEMCrypto_OpenSession: starts! SID=0xb13d5960
D/DrmWidevineDash(  310): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  310): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: starts! randomData=0xb7ab4c10, dataLength=8
D/DrmWidevineDash(  310): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7bbb518, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  310): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  310): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  310): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  310): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  310): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: starts! deviceID=0xb7c06e10, idLength=0xbef412b0
,D/DrmWidevineDash(  310): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  310): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  310): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  310): hlos api version =  9
D/DrmWidevineDash(  310): tz api version =  8
,D/DrmWidevineDash(  310): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  310): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  310): PrepareKeyRequest: nonce=2248172093
D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7bbb518
D/DrmWidevineDash(  310): message_length=1626, signature=0xb7ac1eb8, signature_length=3203666580
,D/DrmWidevineDash(  310): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  310): CdmEngine::CloseSession
D/DrmWidevineDash(  310): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  310): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  310): L3 Terminate.
D/DrmWidevineDash(  310): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  310): Service_Uninitialize: starts!
D/QSEECOMAPI: (  310): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  310): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  310): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  310): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7831): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7831): dex2oat took 72.615ms (threads: 4)
,I/Adreno-EGL( 7786): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7786): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7786): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7786): Local Branch: 
I/Adreno-EGL( 7786): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7786): Local Patches: NONE
I/Adreno-EGL( 7786): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7786): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7786): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7786): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7786): Local Branch: 
I/Adreno-EGL( 7786): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7786): Local Patches: NONE
I/Adreno-EGL( 7786): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7786): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7786): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7786): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7786): Local Branch: 
I/Adreno-EGL( 7786): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7786): Local Patches: NONE
I/Adreno-EGL( 7786): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7786): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7786): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7786): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7786): Local Branch: 
I/Adreno-EGL( 7786): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7786): Local Patches: NONE
I/Adreno-EGL( 7786): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6245): Classify the device as Phone.
,I/CheckinTask( 6245): Sending checkin request (9571 bytes)
,I/CheckinRequestBuilder( 6245): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6245): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6245): Classify the device as Phone.
,I/CheckinTask( 6245): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6245): Checking schedule, now: 1452860569080 next: 1453461706071
I/CheckinService( 6245): active receiver: disabled
,D/CheckinService( 6245): Recording last checkin time for package unspecified as 1452860569090
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7851 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7851): Register our PhoneStateListener
,V/SetupWizard( 7851): Connected to Gservices successfully
,D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Killing 7615:com.google.android.talk/u0a70 (adj 13): empty #7
,I/ActivityManager(  883): Killing 7488:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7615/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7488/cgroup.procs: No such file or directory
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7873 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@240a2713
,I/GCoreNlp( 1739): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1570): Deferring update until onResume
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7910 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7916 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7715:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_7715/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7678:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7678/cgroup.procs: No such file or directory
,W/ResourcesManager( 7916): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7916): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7916): MmsConfig.loadMmsSettings
I/Babel_SMS( 7916): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7916): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7916): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7916): MmsConfig.loadFromResources
,E/Babel_SMS( 7916): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7916): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7916): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7916): startup - clean
,I/Babel   ( 7916): deleted: false for 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7968 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 7916): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7916): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7916): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7916): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7916): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7916): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7916): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7916): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 7968): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7987 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7851:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7851/cgroup.procs: No such file or directory
,W/asset   ( 7987): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7987): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7987): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7987): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6245): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6245): Null package name or gms related package.  Ignoreing.
,I/vclib   ( 7916): onServiceConnected
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@26ccc6ac new=com.google.android.velvet.VelvetApplication@26ccc6ac
,I/UpdateIcingCorporaServi( 7873): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Babel   ( 7916): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7916): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7916): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8014 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6245): updateResources: need to parse f{com.google.android.gms}
,V/JNIHelp ( 7916): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 7873): UpdateCorporaTask done [took 145 ms] updated apps [took 145 ms] 
,W/System  ( 7916): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7916): Installed default security provider GmsCore_OpenSSL
,I/art     (  883): Explicit concurrent mark sweep GC freed 18891(971KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.496ms total 116.524ms
,I/ActivityManager(  883): Killing 7786:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/ResourcesManager( 8014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_7786/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1410): run()
I/Keyboard.Facilitator( 1410): flushDynamicLanguageModels()
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8048 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ConfigService( 1739): onCreate
,D/Finsky  ( 8048): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8048): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8048): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8048): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8048): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 8048): Skipping gmscore version check
D/Finsky  ( 8048): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 8048): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8048): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  883): Killing 7910:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_7910/cgroup.procs: No such file or directory
,I/Icing   ( 6245): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6245): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 7987:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_7987/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7873:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_7873/cgroup.procs: No such file or directory
,I/ConfigService( 1739): onDestroy
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {569c6a0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {1cb9154b, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {1cb9154b, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  883): done {569c6a0, *alarm*:android.intent.action.TIME_TICK} [51ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310786, SEQNUM=4493, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-431, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310709, SEQNUM=4496, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-554, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311859, SEQNUM=4497, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-637, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310960, SEQNUM=4503, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-706, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311194, SEQNUM=4504, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1054, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  883): send {569c6a0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {df353, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  883): send {224d1b28, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  883): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8124 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
V/AlarmManager(  883): done {df353, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [59ms]
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.224ms
,V/AlarmManager(  883): done {569c6a0, *alarm*:android.intent.action.TIME_TICK} [114ms]
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.017ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.135ms
,I/GAv4    ( 8124): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8124):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8124):   adb logcat -s GAv4
,W/GAv4    ( 8124): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8124): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8124): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  883): done {224d1b28, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [301ms]
,I/ActivityManager(  883): Killing 7916:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7916/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=253, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310310, SEQNUM=4511, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-1141, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=251, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311453, SEQNUM=4512, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-113, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  883): send {569c6a0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {20af041, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  883): done {569c6a0, *alarm*:android.intent.action.TIME_TICK} [43ms]
,V/AlarmManager(  883): done {20af041, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [97ms]
,I/GoogleURLConnFactory( 1739): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1739): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1739): Server returned 404
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=250, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310558, SEQNUM=4518, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2118, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=250, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310852, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=249, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311419, SEQNUM=4521, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-27, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=249, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311129, SEQNUM=4523, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-192, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2440): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  883): send {569c6a0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {1dea09ca, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  883): done {1dea09ca, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [26ms]
,V/AlarmManager(  883): done {569c6a0, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  883): send {df353, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,I/ProcessStatsService(  883): Prepared write state in 24ms
,V/AlarmManager(  883): send {569c6a0, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {2c7fd80, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  883): send {28919e58, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  883): send {344f6bb1, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  883): done {df353, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [50ms]
,I/ProcessStatsService(  883): Prepared write state in 16ms
,V/AlarmManager(  883): done {2c7fd80, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [84ms]
,V/AlarmManager(  883): done {569c6a0, *alarm*:android.intent.action.TIME_TICK} [113ms]
,V/AlarmManager(  883): done {28919e58, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [116ms]
,V/AlarmManager(  883): done {344f6bb1, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [124ms]
,I/EventLogService( 6245): Aggregate from 1452860565821 (log), 1452859869601 (data)
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  883): Pruning old procstats: /data/system/procstats/state-2016-01-14-13-49-22.bin
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  883): send {569c6a0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {3d21a321, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  883): send {138cb346, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  883): send {1fabd907, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  883): done {569c6a0, *alarm*:android.intent.action.TIME_TICK} [49ms]
,V/AlarmManager(  883): done {3d21a321, *walarm*:com.motorola.ccc.cce.alarmintent} [141ms]
,V/AlarmManager(  883): done {138cb346, *walarm*:com.motorola.ccc.cce.alarmintent} [163ms]
,V/AlarmManager(  883): done {1fabd907, *walarm*:com.motorola.ccc.cce.alarmintent} [177ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8233): 
D/AndroidRuntime( 8233): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8233): CheckJNI is OFF
D/AndroidRuntime( 8233): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10451 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 6385:com.test.thalitest/u0a451 (adj 9): stop com.test.thalitest
I/WindowState(  883): WIN DEATH: Window{1298ebd1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  883): Client connection lost with reason: 4
W/PackageSettings(  883): Skipping PackageSetting{171bc71b com.example.hello/10440} due to missing metadata
I/ActivityManager(  883):   Force finishing activity ActivityRecord{22133862 u0 com.test.thalitest/.MainActivity t6}
W/ActivityManager(  883): Spurious death for ProcessRecord{3ab5ba34 6385:com.test.thalitest/u0a451}, curProc for 6385: null
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10451 user=0: pkg removed
I/ActivityManager(  883):   Force finishing activity ActivityRecord{22133862 u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  883): Duplicate finish request for ActivityRecord{22133862 u0 com.test.thalitest/.MainActivity t6 f}
I/art     ( 2977): Explicit concurrent mark sweep GC freed 12020(2MB) AllocSpace objects, 36(576KB) LOS objects, 39% free, 7MB/12MB, paused 784us total 41.707ms
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1410): resetDictionaries() : en_US
W/GeofencerStateMachine( 1739): Ignoring removeGeofence because network location is disabled.
I/art     ( 1570): Explicit concurrent mark sweep GC freed 5049(311KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 486us total 91.456ms
I/Keyboard.Facilitator.DecoderInitializer( 1410): run()
I/Decoder ( 1410): createOrResetDecoder
D/VoicemailCleanupService( 7968): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8267 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  883): Explicit concurrent mark sweep GC freed 28909(1917KB) AllocSpace objects, 11(264KB) LOS objects, 33% free, 20MB/30MB, paused 1.975ms total 179.311ms
I/ConfigService( 1739): onCreate
I/art     (  883): WaitForGcToComplete blocked for 10.197ms for cause Explicit
W/asset   ( 8267): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8267): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8267): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8267): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1410): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1410): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1410): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1410): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1410): run()
I/StatsUtilsManager( 1410): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1410): shouldRecordStats() = Too Soon
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8290 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  883): removeObsoleteFile: deleting file=6_task.xml
I/ActivityManager(  883): Killing 8014:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  883): Explicit concurrent mark sweep GC freed 7114(389KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.619ms total 188.783ms
I/Launcher( 1570): Deferring update until onResume
W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_8014/cgroup.procs: No such file or directory
D/AndroidRuntime( 8233): Shutting down VM
W/ContextImpl( 8290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6245): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6245): Reading stored module config
D/AccountUtils( 6245): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6245): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6245): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6245): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6245): App measurement is starting up, version: 8489
I/GMPM-SVC( 6245): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1739): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1739): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8321 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 6245): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6245): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6245): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6245): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6245): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6245): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6245): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6245): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6245): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6245): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6245): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6245): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6245): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/ChimeraCfgMgr( 6245): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6245): Module APK com.google.android.play.games already loaded
W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@26ccc6ac new=com.google.android.velvet.VelvetApplication@26ccc6ac
I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8344 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/Icing   ( 6245): doRemovePackageData com.test.thalitest
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
E/ConnectivityChangeReceiver( 6245): Ignoring connectivity change
E/BaseAppContext( 6245): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
D/ConnectivityService(  883): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6245): CM callback handler got msg 524290
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
E/SQLiteLog( 6245): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
--------- beginning of crash
E/AndroidRuntime( 6245): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6245): Process: com.google.android.gms, PID: 6245
E/AndroidRuntime( 6245): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6245): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6245): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6245): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6245): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6245): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6245): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6245): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BaseAppContext( 6245): Using Auth Proxy for data requests.
I/Process ( 6245): Sending signal. PID: 6245 SIG: 9
D/ConnectivityService(  883): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@22090525)
D/ConnectivityService(  883): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiService(  883): Client connection lost with reason: 4
E/ConnectivityService(  883): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  883): Process com.google.android.gms (pid 6245) has died
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1296ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11296ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21296ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21296ms
E/native  ( 1410): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1410): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8384 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
E/native  ( 1410): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1410): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp

```
