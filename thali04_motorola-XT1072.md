#### Test 558973767bac5c9_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6512): 
D/AndroidRuntime( 6512): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6512): CheckJNI is OFF
D/AndroidRuntime( 6512): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  895): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  895): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6531 uid=10445 gids={50445, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6512): Shutting down VM
V/ActivityManager(  895): Display changed displayId=0
W/ContextImpl( 1493): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1493): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6531): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6531): Time to load native libraries: 7 ms (timestamps 7316-7323)
I/LibraryLoader( 6531): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6531): Binding Chromium to main looper Looper (main, tid 1) {6fe879d}
,I/LibraryLoader( 6531): Expected native library version number "",actual native library version number ""
I/chromium( 6531): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6531): Initializing chromium process, singleProcess=true
,W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6531): ApplicationContext is null in ApplicationStatus
,W/chromium( 6531): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6531): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6531): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6531): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6531): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6531): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6531): Local Branch: 
I/Adreno-EGL( 6531): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6531): Local Patches: NONE
I/Adreno-EGL( 6531): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  895): Message: 20
D/BluetoothManagerService(  895): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b13941f:true
,W/ActivityManager(  895): Activity pause timeout for ActivityRecord{e92e727 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6531): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6531): CordovaWebView is running on device made by: motorola
,W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6531): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6531): Render dirty regions requested: true
D/Atlas   ( 6531): Validating map...
W/chromium( 6531): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/art     (  895): Explicit concurrent mark sweep GC freed 35235(1735KB) AllocSpace objects, 2(213KB) LOS objects, 33% free, 20MB/30MB, paused 1.456ms total 134.347ms
I/OpenGLRenderer( 6531): Initialized EGL, version 1.4
D/OpenGLRenderer( 6531): Enabling debug mode 0
I/Keyboard.Facilitator( 1430): onFinishInput()
I/LaunchCheckinHandler(  895): Displayed com.test.thalitest/.MainActivity,cp,ca,1119
I/ActivityManager(  895): Displayed com.test.thalitest/.MainActivity: +1s49ms (total +1s119ms)
W/IInputConnectionWrapper( 6531): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6531): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6531): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6531): Cannot call determinedVisibility() - never saw a connection for the pid: 6531
D/JsMessageQueue( 6531): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6531): JniHelper::setJavaVM(0xb8ea5310), pthread_self() = -1188872728
,I/chromium( 6531): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6531): Initializing JXcore engine
W/jxcore-log( 6531): JXcore engine is ready
,W/Thread-782( 6579): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10445 path="socket:[5561]" dev="sockfs" ino=5561 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-782( 6579): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10445 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-782( 6579): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10445 path="socket:[7557]" dev="sockfs" ino=7557 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-782( 6579): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10445 path="socket:[27794]" dev="sockfs" ino=27794 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6531): Starting JXcore engine
,W/jxcore-log( 6531): Platform android
W/jxcore-log( 6531): 
W/jxcore-log( 6531): Process ARCH arm
W/jxcore-log( 6531): 
,I/jxcore-log( 6531): JXcore Cordova bridge is ready!
I/jxcore-log( 6531): 
W/jxcore-log( 6531): JXcore engine is started
,I/jxcore-log( 6531): Toggling radios to true
I/jxcore-log( 6531): 
,D/BluetoothAdapter( 6531): enable(): BT is already enabled..!
,D/WifiService(  895): New client listening to asynchronous messages
,D/WifiService(  895): setWifiEnabled: true pid=6531, uid=10445
E/WifiService(  895): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6531): Radios toggled
I/jxcore-log( 6531): 
,I/jxcore-log( 6531): My device name is: motorola-XT1072
I/jxcore-log( 6531): 
,I/wpa_supplicant( 1425): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  295):  STA Disconnected !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  295): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1425): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  895): WifiStateMachine: Leaving Connected state
D/Tethering(  895): InitialState.processMessage what=4
E/WifiStateMachine(  895): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  895): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  895): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  895): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/wpa_supplicant( 1425): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
,W/Settings(  895): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  895): ApnList is empty for checkDunConfigured()
D/Tethering(  895):  upstream interface types: 
D/Tethering(  895):  1
,D/Tethering(  895):  5
D/Tethering(  895):  7
D/Tethering(  895):  0
,E/WifiStateMachine(  895): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  895): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  895): do suspend true
,D/Tethering(  895): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService(  895): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  895): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1425): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  291): Clearing all IP addresses on wlan0
,D/TCMD    (  474): NL - Read 60 bytes from update socket.
D/TCMD    (  474): NL - ignore NL message, type = 21
D/TCMD    (  474): Listening for incoming client connection request
,E/WifiStateMachine(  895): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  895): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiMetrics(  895): connected time updated 120329
D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  895): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  895): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1726): Read error: ssl=0xb9224798: I/O error during system call, Connection timed out
,V/NativeCrypto( 1726): SSL shutdown failed: ssl=0xb9224798: I/O error during system call, Broken pipe
,D/ConnectivityService(  895): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/ActivityManager(  895): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6597 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1425): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  895): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1425): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  895): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  895): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  895): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  895): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  895): do suspend true
D/WifiP2pService(  895): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  895): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1425): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  291): Clearing all IP addresses on wlan0
,D/ConnectivityService(  895): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine(  895): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  895): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  895): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1304): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Disconnected - quitting
,D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  895): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,E/ConnectivityService(  895): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1304): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1304): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6597): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  895): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  895): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  895): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  895): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  895): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  895): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  895): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  895): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  895): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6629 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 22.655ms
,I/ActivityManager(  895): Killing 6295:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 22.913ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.298ms
,W/libprocessgroup(  895): failed to open /acct/uid_10057/pid_6295/cgroup.procs: No such file or directory
,W/ResourcesManager( 6629): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  295): Event received = WPS-AP-AVAILABLE 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,E/WifiStateMachine(  895): [1,452,693,239,776 ms] noteScanEnd no scan source
I/wpa_supplicant( 1425): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  295): Event received = Trying to associate with
D/WifiMonitor(  895): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1425): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiStateMachine(  895): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3f1dd001 sup_state=SCANNING debouncing=false
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  895): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  474): NL - Read 312 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 192 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1425): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  295): Event received = Associated with c0:ff:d4
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/Tethering(  895): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
W/Settings(  895): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TCMD    (  474): Listening for incoming client connection request
E/Tethering(  895): ApnList is empty for checkDunConfigured()
D/Tethering(  895):  upstream interface types: 
D/Tethering(  895):  0
D/Tethering(  895):  1
D/Tethering(  895):  5
D/Tethering(  895):  7
,E/WifiStateMachine(  895): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1425): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  295): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1425): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295):  STA Connected !!
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,E/MDMCTBK (  295): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  295): get_freq !!, resp=2412
I/MDMCTBK (  295): get_freq !!, Strip data
I/MDMCTBK (  295): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  295): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  295): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  295): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1208033456
I/MDMCTBK (  295): return from set_get_from_wpa_supplicant
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  895): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  895): setDetailed state send new extra info"NG700"
D/Tethering(  895): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  295): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  295): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  295): , reply_len: 3, ret: 0
E/MDMCTBK (  295): MdmCutbackHndler, resp=OK
E/MDMCTBK (  295): 
,D/MDMCTBK (  295): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  895): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  895): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  895): Network connection established
E/WifiStateMachine(  895): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  895): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  895): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  895): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  895): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  895): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  895): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  895): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  895): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  895): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  895): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  291): Setting iface cfg
E/WifiStateMachine(  895): Start Dhcp Watchdog 2
E/WifiStateMachine(  895): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  895): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  895): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  895): do suspend false
,E/wpa_supplicant( 1425): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  895): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1425): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  895): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d6a15dd target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  895): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d6a15dd target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6629): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6629): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6629): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6629): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6629): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6629): MmsConfig.loadFromResources
,E/Babel_SMS( 6629): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6629): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6629): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6629): startup - clean
,I/Babel   ( 6629): deleted: false for 0
,E/DHCPCD  ( 6668): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 6668): version 5.5.6 starting
E/DHCPCD  ( 6668): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6668): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6668): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/VideoCapabilities( 6629): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6629): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 6629): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6629): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6629): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6629): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6629): Unrecognized profile 2130706433 for video/avc
,D/DHCPCD  ( 6668): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6668): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6668): wlan0: sending REQUEST (xid 0xdc13c116), next in 3.87 seconds
W/VideoCapabilities( 6629): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  895): Killing 6336:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/DHCPCD  ( 6668): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6668): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6668): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  474): NL - Read 60 bytes from update socket.
D/TCMD    (  474): NL - ignore NL message, type = 20
D/TCMD    (  474): Listening for incoming client connection request
D/DHCPCD  ( 6668): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6668): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6668): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
W/libprocessgroup(  895): failed to open /acct/uid_10090/pid_6336/cgroup.procs: No such file or directory
E/WifiStateMachine(  895): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  895): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/DHCPCD  ( 6668): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/vclib   ( 6629): onServiceConnected
,W/Babel   ( 6629): Attempted to change video mute state without an active call.
,E/WifiStateMachine(  895): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  895): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  895): do suspend true
,D/WifiP2pService(  895): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  895): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  895): WifiStateMachine DHCP successful
E/WifiStateMachine(  895): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  895): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  895): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  895): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  895): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  895): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  895): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1304): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  895): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  895): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  895): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  895): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  895): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  895): Setting Dns servers for network 101 to [/192.168.1.1]
,E/WifiStateMachine(  895): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/Nat464Xlat(  895): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  895): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  895): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  895): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  895):    accepting network in place of null
,D/ConnectivityService(  895): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  895): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1304): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  895): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): DefaultState{ when=-11ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1304): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
,D/Checkin (  895): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  895): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  895): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1304): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 13:54:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452693241007], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452693240986]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  895): Validated
D/ConnectivityService(  895): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  895): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  895): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  895): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1304): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1304): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1304): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1548): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1548): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1304): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1304): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1304): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  895): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  895): MasterInitialState.processMessage what=3
,D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1493): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1493): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2670): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  895): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6730 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  895): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1493): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1493): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/ActivityManager(  895): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6747 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/CCE     ( 2670): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2670): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2670): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2670): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2670): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2670): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2670): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2670): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2670): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2670): [debug] > CusSM.onRadioDown
,W/ResourcesManager( 6747): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MusicStore( 6730): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6730): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6730): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6730): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6730): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6730): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6730): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6730): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6730): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a819fc9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6730): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6730): GMSCore installation verified
,I/ConfigStore( 6730): Config Database version: 1
,I/MediaRouter( 6730): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6730): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6730): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  895): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6799 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6730): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6730): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  895): Killing 6206:com.android.vending/u0a32 (adj 15): empty #7
,V/Mms     ( 6799): mnc/mcc: 
,V/Mms     ( 6799): tag: int value: recipientLimit - 20
,V/Mms     ( 6799): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6799): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6799): tag: int value: maxSubjectLength - 80
V/Mms     ( 6799): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6799): tag: bool value: enableGroupMms - false
V/Mms     ( 6799):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  895): failed to open /acct/uid_10032/pid_6206/cgroup.procs: No such file or directory
,I/ActivityManager(  895): Killing 6629:com.google.android.talk/u0a70 (adj 15): empty #7
,E/global frequency( 2670): no tags to log
,D/Checkin ( 2670): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/ConnectivityService(  895): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  895): failed to open /acct/uid_10070/pid_6629/cgroup.procs: No such file or directory
,V/AlarmManager(  895): send {3daf0316, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  895): send {381d10b5, *walarm*:com.google.android.intent.action.SEND_IDLE}
,D/Central_PollingManager( 1493): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1493): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Tethering(  895): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 6730): type=WIFI subType= reason=null isConnected=true
,D/Central_PollingManager( 1493): now: 195921 ,futureTime: 86475617
D/Central_PollingManager( 1493): Polling alarm set to expire at: 86475617 Current Time: 195921
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1566): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/ResourcesManager( 6799): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  895): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6826 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  895): Explicit concurrent mark sweep GC freed 52703(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.655ms total 131.225ms
,V/AlarmManager(  895): done {3daf0316, *alarm*:android.intent.action.TIME_TICK} [312ms]
,I/ActivityManager(  895): Killing 6597:com.motorola.context/u0a8 (adj 15): empty #7
,D/PhoneMonitor( 6826): Register our PhoneStateListener
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  895): failed to open /acct/uid_10008/pid_6597/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6826): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6826): onReceive CONNECTIVITY_CHANGE networkType=1
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1566): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  895): Killing 6123:android.process.acore/u0a7 (adj 15): empty #7
,I/art     ( 1493): Explicit concurrent mark sweep GC freed 55949(3MB) AllocSpace objects, 36(1229KB) LOS objects, 39% free, 7MB/12MB, paused 898us total 51.102ms
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,W/libprocessgroup(  895): failed to open /acct/uid_10007/pid_6123/cgroup.procs: No such file or directory
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
W/ProcessCpuTracker(  895): Skipping unknown process pid 6740
,I/CheckinService( 6399): Checkin interval check for package: unspecified last checkin: 1452693164075 min interval config: 0 actual interval: 80313
W/ProcessCpuTracker(  895): Skipping unknown process pid 6743
E/PhoneInterfaceManager( 1566): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/CheckinService( 6399): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6399): SYNC; picasa accounts
,D/NetworkLogImpl( 6399): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6399): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/CheckinService( 6399): Checking schedule, now: 1452693244469 next: 1452693194054
I/CheckinService( 6399): active receiver: enabled
,I/iu.UploadsManager( 6399): num queued entries: 0
I/iu.UploadsManager( 6399): num updated entries: 0
,I/iu.SyncManager( 6399): NEXT; no task
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/CheckinService( 6399): Preparing to send checkin request
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/EventLogService( 6399): Accumulating logs since 1452693160989
,I/ActivityManager(  895): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6862 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2670): now: 196551 ,futureTime: 9223372036854775807
,D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2670): now: 196551 ,futureTime: 9223372036854775807
,D/PollingManager( 2670): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2670): now: 196551 ,futureTime: 9223372036854775807
D/OtaApp  ( 2670): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2670): [debug] > PollingManagerService, now: 196588 ,futureTime: 15009357
,D/OtaApp  ( 2670): [debug] > Polling alarm set to expire at: 15009357 Current Time: 196589
,I/art     ( 1493): Explicit concurrent mark sweep GC freed 4232(177KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 614us total 31.367ms
,D/MMApiProvisionService( 2670): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2670): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2670): createDeviceIdOrLogin update_device
D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2670): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2670): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2670): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2670): createDeviceIdOrLogin update_device
D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,E/WifiStateMachine(  895): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  895): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  895): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  895): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1304): CM callback handler got msg 524295
E/WifiStateMachine(  895): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/CheckinRequestBuilder( 6399): Checkin reason type: 8 attempt count: 1
D/WifiService(  895): New client listening to asynchronous messages
E/ActivityThread( 6399): Failed to find provider info for com.google.android.wearable.settings
I/art     ( 2670): Explicit concurrent mark sweep GC freed 17903(1044KB) AllocSpace objects, 2(55KB) LOS objects, 39% free, 11MB/19MB, paused 1.294ms total 86.073ms
,I/art     (  895): Explicit concurrent mark sweep GC freed 9439(456KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.182ms total 116.997ms
,D/MMApiProvisionService( 2670): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2670): set mOutstandingReq to true.
I/ Nonce  ( 2670):  Nonce getNonce 
I/ Nonce  ( 2670):  Nonce Request 
I/ Nonce  ( 2670):  Nonce execute Request 
,D/MMApiWebService( 2670): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2670): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2670): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2670): createDeviceIdOrLogin update_device
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2670): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2670): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2670): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2670): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2670): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2670): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2670): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2670): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2670): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MMApiWebService( 2670): generating token using payload instead of using session token
,I/ActivityManager(  895): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6882 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/OtaApp  ( 2670): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/global frequency( 2670): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2670): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2670): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/ Nonce  ( 2670):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2670): publish the event [tag = MOT_CHECKIN event name = LOG]
I/MMApiWSBase( 2670): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2670): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2670): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,W/ResourcesManager( 6882): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  895): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6905 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6905): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6905): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel_SMS( 6882): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6882): MmsConfig.loadMmsSettings
I/Babel_SMS( 6882): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6882): MmsConfig.loadFromDatabase
,I/MultiDex( 6905): VM with version 2.1.0 has multidex support
I/MultiDex( 6905): install
I/MultiDex( 6905): VM has multidex support, MultiDex support library is disabled.
,E/Babel_SMS( 6882): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6882): MmsConfig.loadFromResources
,E/Babel_SMS( 6882): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6882): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,V/JNIHelp ( 6905): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 6882): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6882): startup - clean
,I/Babel   ( 6882): deleted: false for 0
,W/ActivityThread( 6905): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6905): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16c47d96: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6905): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  895): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6935 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 6905): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6905): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6905): Install completed successfully. count=14 extracted=0
,W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
,D/WVCdm   (  297): Instantiating CDM.
,W/AudioCapabilities( 6882): Unsupported mime audio/amr-wb-plus
I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/VideoCapabilities( 6882): Unsupported mime video/mpeg2
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,I/VideoCapabilities( 6882): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6882): onServiceConnected
W/Babel   ( 6882): Attempted to change video mute state without an active call.
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xbeb744e0
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7e40fd0, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e42640, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f79708, idLength=0xb54cb730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=2777008808
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e43130
D/DrmWidevineDash(  297): message_length=1591, signature=0xb7e43770, signature_length=3041703700
,I/Babel   ( 6882): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  895): Killing 6730:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/art     ( 6882): Suspending all threads took: 5.329ms
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  895): failed to open /acct/uid_10080/pid_6730/cgroup.procs: No such file or directory
,I/ Nonce  ( 2670):  Nonce Reponse 
D/        ( 2670): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"ce413378-e239-4d3f-a784-f86d5edbf3b3"}
,D/MMApiWSBase( 2670): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2670):  Nonce Handle Reponse 
D/MMApiProvisionService( 2670): mOutstandingReq set to false
,D/MMApiProvisionService( 2670):  pTime 1452672215335 sExp 172742 cTime 1452693246319 tTime 1452844957335
D/MMApiProvisionService( 2670):  No login Required 
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6935): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6935): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6935): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6935): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6935): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6935):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6935):   adb logcat -s GAv4
,W/GAv4    ( 6935): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6935): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6935): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb0eb9960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7f2df50, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e42640, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f79748, idLength=0xbeb742b0
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=2450951439
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e431e8
D/DrmWidevineDash(  297): message_length=1626, signature=0xb7e33e60, signature_length=3199681172
,I/WebViewFactory( 6935): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6935): Time to load native libraries: 2 ms (timestamps 8720-8722)
I/LibraryLoader( 6935): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6935): Binding Chromium to main looper Looper (main, tid 1) {6b57846}
,I/LibraryLoader( 6935): Expected native library version number "",actual native library version number ""
,I/chromium( 6935): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6935): Initializing chromium process, singleProcess=true
,W/art     ( 6935): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6935): ApplicationContext is null in ApplicationStatus
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,W/DataUsage( 2670): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,W/chromium( 6935): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6935): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6935): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6935): Local Branch: 
I/Adreno-EGL( 6935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6935): Local Patches: NONE
I/Adreno-EGL( 6935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 6989): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/AudioManagerAndroid( 6935): Requires BLUETOOTH permission
,I/NSApplication( 6935): Starting up...
,I/ActivityManager(  895): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7007 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  895): Killing 6747:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/dex2oat ( 6989): dex2oat took 83.727ms (threads: 4)
,I/Adreno-EGL( 6905): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6905): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6905): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6905): Local Branch: 
I/Adreno-EGL( 6905): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6905): Local Patches: NONE
I/Adreno-EGL( 6905): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6905): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6905): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6905): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6905): Local Branch: 
I/Adreno-EGL( 6905): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6905): Local Patches: NONE
I/Adreno-EGL( 6905): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  895): failed to open /acct/uid_10090/pid_6747/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6905): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6905): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6905): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6905): Local Branch: 
I/Adreno-EGL( 6905): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6905): Local Patches: NONE
I/Adreno-EGL( 6905): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6905): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6905): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6905): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6905): Local Branch: 
I/Adreno-EGL( 6905): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6905): Local Patches: NONE
I/Adreno-EGL( 6905): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  895): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7030 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  895): Killing 6799:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10023/pid_6799/cgroup.procs: No such file or directory
,W/ResourcesManager( 7030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6399): Classify the device as Phone.
,I/art     ( 6364): Explicit concurrent mark sweep GC freed 1588(71KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 361us total 26.260ms
,I/CheckinTask( 6399): Sending checkin request (9521 bytes)
,I/ActivityManager(  895): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7059 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.190ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 18.859ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.284ms
,I/ActivityManager(  895): Killing 6862:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  895): Explicit concurrent mark sweep GC freed 9496(455KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.669ms total 128.967ms
,I/ActivityManager(  895): Killing 6826:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 7059): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  895): failed to open /acct/uid_10088/pid_6862/cgroup.procs: No such file or directory
W/libprocessgroup(  895): failed to open /acct/uid_10035/pid_6826/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2670): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2670): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2670): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2670): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2670): onServiceConnected()
D/GetNotificationsWS( 2670): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2670): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2670): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  895): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7090 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6399): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6399): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6399): Classify the device as Phone.
,I/CheckinTask( 6399): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6399): Checking schedule, now: 1452693248448 next: 1453294385444
I/CheckinService( 6399): active receiver: disabled
,I/MusicStore( 7090): Database version: 120
,D/CheckinService( 6399): Recording last checkin time for package unspecified as 1452693248516
,I/ActivityManager(  895): Killing 6935:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,E/libprocessgroup(  895): failed to kill 1 processes for processgroup 6935
,I/ActivityManager(  895): Killing 6882:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  895): failed to open /acct/uid_10070/pid_6882/cgroup.procs: No such file or directory
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7090): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7090): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7090): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7090): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7090): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a819fc9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7090): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7090): GMSCore installation verified
,I/ConfigStore( 7090): Config Database version: 1
,I/MediaRouter( 7090): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7090): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7090): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7090): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  895): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7132 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7090): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7090): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  895): Killing 7007:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10052/pid_7007/cgroup.procs: No such file or directory
,V/Mms     ( 7132): mnc/mcc: 
V/Mms     ( 7132): tag: int value: recipientLimit - 20
V/Mms     ( 7132): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7132): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7132): tag: int value: maxSubjectLength - 80
V/Mms     ( 7132): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7132): tag: bool value: enableGroupMms - false
V/Mms     ( 7132):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7132): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  895): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7170 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7030:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,D/PhoneMonitor( 7170): Register our PhoneStateListener
,W/libprocessgroup(  895): failed to open /acct/uid_10090/pid_7030/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7170): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  895): Killing 7059:android.process.acore/u0a7 (adj 15): empty #7
,D/BatteryService(  895): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311543, SEQNUM=4459, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14723, POWER_SUPPLY_CHARGE_COUNTER=-509, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  895): failed to open /acct/uid_10007/pid_7059/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2526): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2526): Disconnected process message: 10, size: 0
,I/CheckinService( 6399): Checkin interval check for package: unspecified last checkin: 1452693248516 min interval config: 0 actual interval: 1864
,I/ActivityManager(  895): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7193 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6399): Checking schedule, now: 1452693250433 next: 1452693278444
I/CheckinService( 6399): active receiver: disabled
,I/ActivityManager(  895): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7211 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7090:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10080/pid_7090/cgroup.procs: No such file or directory
,W/ResourcesManager( 7211): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7211): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7211): MmsConfig.loadMmsSettings
I/Babel_SMS( 7211): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7211): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7211): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7211): MmsConfig.loadFromResources
E/Babel_SMS( 7211): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7211): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7211): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7211): startup - clean
,I/Babel   ( 7211): deleted: false for 0
,I/ActivityManager(  895): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7250 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7211): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7211): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7211): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7211): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7211): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7211): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7211): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7211): onServiceConnected
,W/Babel   ( 7211): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7250): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7250): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7250):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7250):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7250): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7250): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7211): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  895): Killing 7132:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7250): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7250): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7250): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7250): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  895): failed to open /acct/uid_10023/pid_7132/cgroup.procs: No such file or directory
,I/WebViewFactory( 7250): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7250): Time to load native libraries: 1 ms (timestamps 4073-4074)
I/LibraryLoader( 7250): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7250): Binding Chromium to main looper Looper (main, tid 1) {6b57846}
,I/LibraryLoader( 7250): Expected native library version number "",actual native library version number ""
,I/chromium( 7250): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7250): Initializing chromium process, singleProcess=true
,W/art     ( 7250): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7250): ApplicationContext is null in ApplicationStatus
,W/chromium( 7250): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7250): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7250): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7250): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7250): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7250): Local Branch: 
I/Adreno-EGL( 7250): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7250): Local Patches: NONE
I/Adreno-EGL( 7250): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7250): Requires BLUETOOTH permission
,I/NSApplication( 7250): Starting up...
,I/ActivityManager(  895): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7323 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  895): Killing 7170:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10035/pid_7170/cgroup.procs: No such file or directory
,I/art     (  895): Explicit concurrent mark sweep GC freed 11757(610KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.551ms total 111.867ms
,I/ActivityManager(  895): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7342 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7193:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10088/pid_7193/cgroup.procs: No such file or directory
,W/ResourcesManager( 7342): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  895): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7365 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7211:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  895): Killing 7250:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,E/libprocessgroup(  895): failed to kill 1 processes for processgroup 7250
W/libprocessgroup(  895): failed to open /acct/uid_10070/pid_7211/cgroup.procs: No such file or directory
,I/ContactLocale( 7365): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,V/AlarmManager(  895): done {381d10b5, *walarm*:com.google.android.intent.action.SEND_IDLE} [10000ms]
,I/ActivityManager(  895): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7396 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7396): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7396): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7396): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7396): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7396): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7396): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7396): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a819fc9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7396): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7396): GMSCore installation verified
,I/ConfigStore( 7396): Config Database version: 1
,I/MediaRouter( 7396): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7396): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7396): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7396): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  895): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7437 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 22.395ms
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 529us total 19.888ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 22.372ms
,I/GHttpClientFactory( 7396): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7396): Using platform SSLCertificateSocketFactory
,I/InputReader(  895): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  895): Killing 6905:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7437): mnc/mcc: 
V/Mms     ( 7437): tag: int value: recipientLimit - 20
V/Mms     ( 7437): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7437): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7437): tag: int value: maxSubjectLength - 80
V/Mms     ( 7437): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7437): tag: bool value: enableGroupMms - false
V/Mms     ( 7437):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/BackupManagerService(  895): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  895): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  895): failed to open /acct/uid_10016/pid_6905/cgroup.procs: No such file or directory
,I/BackupManagerService(  895): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  895): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  895): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2bb68286
,I/GCoreNlp( 1726): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1584): Deferring update until onResume
,W/ResourcesManager( 7437): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  895): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7468 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7323:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7468): Register our PhoneStateListener
,W/libprocessgroup(  895): failed to open /acct/uid_10052/pid_7323/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7468): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7468): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  895): Killing 7342:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10090/pid_7342/cgroup.procs: No such file or directory
,I/CheckinService( 6399): Checkin interval check for package: unspecified last checkin: 1452693248516 min interval config: 0 actual interval: 6797
,I/ActivityManager(  895): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7493 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6399): Checking schedule, now: 1452693255383 next: 1452693278444
I/CheckinService( 6399): active receiver: disabled
,I/ActivityManager(  895): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7518 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7365:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10007/pid_7365/cgroup.procs: No such file or directory
,W/ResourcesManager( 7518): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7518): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7518): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7518): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7518): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7518): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7518): MmsConfig.loadFromResources
,E/Babel_SMS( 7518): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7518): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7518): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7518): startup - clean
,I/Babel   ( 7518): deleted: false for 0
,I/ActivityManager(  895): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7559 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7518): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7518): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7518): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7518): onServiceConnected
,W/Babel   ( 7518): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7559): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7559): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7559):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7559):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7559): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7518): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  895): Killing 7396:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7559): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7559): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  895): failed to open /acct/uid_10080/pid_7396/cgroup.procs: No such file or directory
,W/GAv4    ( 7559): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7559): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7559): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  895): Explicit concurrent mark sweep GC freed 17754(901KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.710ms total 114.224ms
,I/WebViewFactory( 7559): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7559): Time to load native libraries: 1 ms (timestamps 9064-9065)
,I/LibraryLoader( 7559): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7559): Binding Chromium to main looper Looper (main, tid 1) {6b57846}
,I/LibraryLoader( 7559): Expected native library version number "",actual native library version number ""
,I/chromium( 7559): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7559): Initializing chromium process, singleProcess=true
,W/art     ( 7559): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7559): ApplicationContext is null in ApplicationStatus
,W/chromium( 7559): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7559): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7559): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7559): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7559): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7559): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7559): Local Branch: 
I/Adreno-EGL( 7559): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7559): Local Patches: NONE
I/Adreno-EGL( 7559): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7559): Requires BLUETOOTH permission
,I/NSApplication( 7559): Starting up...
,I/ActivityManager(  895): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7623 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7437:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10023/pid_7437/cgroup.procs: No such file or directory
,I/ActivityManager(  895): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7645 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  895): Killing 7468:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10035/pid_7468/cgroup.procs: No such file or directory
,W/ResourcesManager( 7645): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  895): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7669 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7518:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7669): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  895): Killing 7493:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  895): failed to open /acct/uid_10070/pid_7518/cgroup.procs: No such file or directory
,W/libprocessgroup(  895): failed to open /acct/uid_10088/pid_7493/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2670): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2670): bindWebServices(): registering our AIDL callback...
I/SundryService( 2670): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2670): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2670): onServiceConnected()
D/GetNotificationsWS( 2670): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2670): unbindWebServices(): un-registering our AIDL callback...
I/PushService( 2670): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  895): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7702 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2670): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2670): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2670): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  895): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1493): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1493): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/WearableService( 1726): callingUid 10016, callindPid: 1726
,D/LocationInitializer( 6399): Restart initialization of location
,D/OtaApp  ( 2670): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2670): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,E/MDM     ( 1726): [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1726): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/OtaApp  ( 2670): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2670): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2670): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2670): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2670): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2670): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,W/GCoreFlp( 1726): No location to return for getLastLocation()
D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
W/FusedLocationProvider( 1726): location=null
,I/Keyboard.Facilitator( 1430): onFinishInput()
,W/IInputConnectionWrapper( 6531): showStatusIcon on inactive InputConnection
,I/ActivityManager(  895): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7734 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/LaunchCheckinHandler(  895): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,221
,D/PhoneMonitor( 7734): Register our PhoneStateListener
,V/SetupWizard( 7734): Connected to Gservices successfully
,I/ActivityManager(  895): Killing 7559:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10081/pid_7559/cgroup.procs: No such file or directory
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  895): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7761 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/PhenotypeConfigurator( 1726): Scheduling Phenotype for one-off execution 1034 seconds from now (1452693259721)
,D/GetConfigurationSnapshotOperation( 1726): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/ActivityManager(  895): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7790 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 29.853ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.279ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.595ms
,I/jxcore-log( 6531): Test app app.js loaded
I/jxcore-log( 6531): 
,I/chromium( 6531): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/ActivityManager(  895): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7807 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7623:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10052/pid_7623/cgroup.procs: No such file or directory
,I/ActivityManager(  895): Killing 7645:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/PhenotypeFlagCommitter( 1726): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
W/ResourcesManager( 7807): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GoogleURLConnFactory( 1726): Using platform SSLCertificateSocketFactory
,W/libprocessgroup(  895): failed to open /acct/uid_10090/pid_7645/cgroup.procs: No such file or directory
,I/art     ( 6364): Explicit concurrent mark sweep GC freed 1814(68KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 815us total 33.621ms
,I/Babel_SMS( 7807): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7807): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7807): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7807): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7807): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7807): MmsConfig.loadFromResources
,E/Babel_SMS( 7807): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7807): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7807): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7807): startup - clean
,I/Babel   ( 7807): deleted: false for 0
,W/VideoCapabilities( 7807): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7807): Unsupported mime audio/amr-wb-plus
,I/ActivityManager(  895): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7845 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7807): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7807): Unsupported profile 4 for video/mp4v-es
,W/asset   ( 7845): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7845): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7845): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7845): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
W/VideoCapabilities( 7807): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7807): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7807): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7807): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6399): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 7761): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1584): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1b35f3f new=com.google.android.velvet.VelvetApplication@1b35f3f
,I/ActivityManager(  895): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7872 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 6399): Null package name or gms related package.  Ignoreing.
,I/vclib   ( 7807): onServiceConnected
,W/Babel   ( 7807): Attempted to change video mute state without an active call.
,I/Icing   ( 6399): updateResources: need to parse f{com.google.android.gms}
I/art     (  895): Explicit concurrent mark sweep GC freed 16077(754KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.481ms total 151.869ms
,W/ResourcesManager( 7872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7807): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7807): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7761): UpdateCorporaTask done [took 229 ms] updated apps [took 229 ms] 
,I/ActivityManager(  895): Killing 7734:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,V/JNIHelp ( 7807): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7807): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7807): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  895): failed to open /acct/uid_10035/pid_7734/cgroup.procs: No such file or directory
,I/ActivityManager(  895): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7906 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7702:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10088/pid_7702/cgroup.procs: No such file or directory
,D/Finsky  ( 7906): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7906): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7906): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7906): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7906): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7906): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7906): Skipping gmscore version check
,D/Finsky  ( 7906): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7906): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  895): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7951 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7790:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10019/pid_7790/cgroup.procs: No such file or directory
,D/TaskPersister(  895): removeObsoleteFile: deleting file=5_task.xml
,D/PhoneMonitor( 7951): Register our PhoneStateListener
,I/ActivityManager(  895): Killing 7845:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10027/pid_7845/cgroup.procs: No such file or directory
,I/CheckinService( 6399): Checkin interval check for package: unspecified last checkin: 1452693248516 min interval config: 0 actual interval: 13434
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 6399): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  895): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7970 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 6399): Checking schedule, now: 1452693261998 next: 1452693278444
I/CheckinService( 6399): active receiver: disabled
,D/Icing   ( 6399): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6399): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  895): Killing 7761:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10039/pid_7761/cgroup.procs: No such file or directory
,I/art     ( 1726): Explicit concurrent mark sweep GC freed 108221(5MB) AllocSpace objects, 32(535KB) LOS objects, 40% free, 15MB/25MB, paused 1.134ms total 178.289ms
,I/art     ( 1726): WaitForGcToComplete blocked for 102.356ms for cause Background
,E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ead9b3f)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@16f27c0c)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2452a955)
,E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33882f6a)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@56aac5b)
,I/ActivityManager(  895): Killing 7669:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10007/pid_7669/cgroup.procs: No such file or directory
,I/CheckinService( 6399): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  895): Killing 7872:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10090/pid_7872/cgroup.procs: No such file or directory
,D/BatteryService(  895): uevent={POWER_SUPPLY_TEMP=292, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310839, SEQNUM=4498, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-569, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2526): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2526): Disconnected process message: 10, size: 0
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  895): send {25f83bf0, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  895): done {25f83bf0, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  895): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311797, SEQNUM=4504, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-611, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2526): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2526): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1726): disconnect managed GoogleApiClient
,V/AlarmManager(  895): send {2d3a6d4e, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  895): send {1894d569, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  895): done {2d3a6d4e, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
,V/AlarmManager(  895): done {1894d569, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [25ms]
,I/CheckinService( 6399): Checkin interval check for package: unspecified last checkin: 1452693248516 min interval config: 0 actual interval: 45447
,I/CheckinService( 6399): Checking schedule, now: 1452693293975 next: 1452693278444
I/CheckinService( 6399): active receiver: enabled
,I/CheckinService( 6399): Preparing to send checkin request
I/EventLogService( 6399): Accumulating logs since 1452693244674
,I/CheckinRequestBuilder( 6399): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6399): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  895): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8038 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8038): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8038): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8038): VM with version 2.1.0 has multidex support
,I/MultiDex( 8038): install
I/MultiDex( 8038): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8038): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8038): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8038): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16c47d96: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8038): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1726): callingUid 10016, callindPid: 1726
,D/AuthorizationBluetoothService( 1726): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6399): Restart initialization of location
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1726): [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1726): No location to return for getLastLocation()
W/FusedLocationProvider( 1726): location=null
,I/art     ( 8038): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8038): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,D/NativeLibraryUtils( 8038): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  297): Instantiating CDM.
I/WVCdm   (  297): CdmEngine::OpenSession
,I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb54cb960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7e40ec8, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e42640, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f79728, idLength=0xbeb742b0
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=894716349
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e9aa10
D/DrmWidevineDash(  297): message_length=1591, signature=0xb7e9b050, signature_length=3199681172
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb54cb960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7e9ad00, dataLength=8
,D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e29360, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7f79748, idLength=0xb55cb730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  297): PrepareKeyRequest: nonce=33718780
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7f2de50
D/DrmWidevineDash(  297): message_length=1625, signature=0xb7e40f38, signature_length=3042752276
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8080): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8080): dex2oat took 72.771ms (threads: 4)
,I/Adreno-EGL( 8038): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8038): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8038): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8038): Local Branch: 
I/Adreno-EGL( 8038): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8038): Local Patches: NONE
I/Adreno-EGL( 8038): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8038): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8038): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8038): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8038): Local Branch: 
I/Adreno-EGL( 8038): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8038): Local Patches: NONE
I/Adreno-EGL( 8038): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8038): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8038): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8038): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8038): Local Branch: 
I/Adreno-EGL( 8038): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8038): Local Patches: NONE
I/Adreno-EGL( 8038): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8038): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8038): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8038): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8038): Local Branch: 
I/Adreno-EGL( 8038): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8038): Local Patches: NONE
I/Adreno-EGL( 8038): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6399): Classify the device as Phone.
,I/CheckinTask( 6399): Sending checkin request (9515 bytes)
,I/CheckinRequestBuilder( 6399): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6399): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6399): Classify the device as Phone.
,I/CheckinTask( 6399): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6399): Checking schedule, now: 1452693296735 next: 1453294433727
I/CheckinService( 6399): active receiver: disabled
,D/CheckinService( 6399): Recording last checkin time for package unspecified as 1452693296747
,V/SetupWizard( 7951): Connected to Gservices successfully
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  895): Killing 7906:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10032/pid_7906/cgroup.procs: No such file or directory
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/InputReader(  895): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  895): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8104 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  895): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  895): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  895): Explicit concurrent mark sweep GC freed 21442(1040KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.768ms total 126.064ms
,I/BackupManagerService(  895): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  895): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  895): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3739028
,I/GCoreNlp( 1726): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1584): Deferring update until onResume
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  895): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8142 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  895): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8161 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7970:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10088/pid_7970/cgroup.procs: No such file or directory
,W/ResourcesManager( 7807): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7807): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8161): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  895): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8184 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 7951:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.031ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 19.262ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.063ms
,W/libprocessgroup(  895): failed to open /acct/uid_10035/pid_7951/cgroup.procs: No such file or directory
,W/asset   ( 8184): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8184): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8184): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8184): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6399): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6399): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1584): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1b35f3f new=com.google.android.velvet.VelvetApplication@1b35f3f
I/UpdateIcingCorporaServi( 8104): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6399): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  895): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8210 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8210): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8104): UpdateCorporaTask done [took 143 ms] updated apps [took 143 ms] 
,I/ActivityManager(  895): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8235 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  895): Killing 8038:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10016/pid_8038/cgroup.procs: No such file or directory
,D/Finsky  ( 8235): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8235): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8235): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8235): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8235): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8235): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8235): Skipping gmscore version check
,I/ActivityManager(  895): Killing 8142:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10019/pid_8142/cgroup.procs: No such file or directory
,D/Finsky  ( 8235): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8235): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6399): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6399): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  895): Killing 8184:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10027/pid_8184/cgroup.procs: No such file or directory
,V/AlarmManager(  895): send {3daf0316, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  895): send {25f83bf0, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  895): done {25f83bf0, *walarm*:android.content.syncmanager.SYNC_ALARM} [8ms]
,V/AlarmManager(  895): done {3daf0316, *alarm*:android.intent.action.TIME_TICK} [47ms]
,I/ActivityManager(  895): Killing 7807:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  895): failed to open /acct/uid_10070/pid_7807/cgroup.procs: No such file or directory
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1430): run()
,I/Keyboard.Facilitator( 1430): flushDynamicLanguageModels()
,I/ConfigService( 1726): onCreate
,I/ConfigService( 1726): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  895): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311069, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-749, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2526): Disconnected process message: 10, size: 0
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6531): --= Surplus to requirements =--
I/jxcore-log( 6531): 
I/jxcore-log( 6531): ****TEST TOOK:  ms ****
I/jxcore-log( 6531): 
I/jxcore-log( 6531): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6531): 
,D/AndroidRuntime( 8303): 
D/AndroidRuntime( 8303): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8303): CheckJNI is OFF
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 8303): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  895): Force stopping com.test.thalitest appid=10445 user=-1: uninstall pkg
,I/ActivityManager(  895): Killing 6531:com.test.thalitest/u0a445 (adj 9): stop com.test.thalitest
,W/PackageSettings(  895): Skipping PackageSetting{36dfc58a com.example.hello/10440} due to missing metadata
,D/WifiService(  895): Client connection lost with reason: 4
,I/WindowState(  895): WIN DEATH: Window{29fb157a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  895):   Force finishing activity ActivityRecord{e92e727 u0 com.test.thalitest/.MainActivity t6}
,I/ActivityManager(  895): Force stopping com.test.thalitest appid=10445 user=0: pkg removed
,I/ActivityManager(  895):   Force finishing activity ActivityRecord{e92e727 u0 com.test.thalitest/.MainActivity t6 f}
,W/ActivityManager(  895): Duplicate finish request for ActivityRecord{e92e727 u0 com.test.thalitest/.MainActivity t6 f}
,I/art     ( 3077): Explicit concurrent mark sweep GC freed 10033(2MB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 7MB/12MB, paused 994us total 38.442ms
,W/ActivityManager(  895): Spurious death for ProcessRecord{354837c9 6531:com.test.thalitest/u0a445}, curProc for 6531: null
,I/InputReader(  895): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1726): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1430): resetDictionaries() : en_US
,D/VoicemailCleanupService( 8161): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  895): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8333 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1584): Explicit concurrent mark sweep GC freed 5063(312KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 481us total 144.093ms
,I/Keyboard.Facilitator.DecoderInitializer( 1430): run()
,I/Decoder ( 1430): createOrResetDecoder
,I/art     (  895): Explicit concurrent mark sweep GC freed 21150(1357KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.830ms total 151.017ms
I/art     (  895): WaitForGcToComplete blocked for 62.337ms for cause Explicit
,W/asset   ( 8333): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8333): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8333): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8333): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ConfigService( 1726): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1430): run()
,D/BackupManagerService(  895): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  895): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  895): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8358 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  895): removeObsoleteFile: deleting file=6_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1430): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1430): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1430): run() : Loading LM = contacts
,I/ActivityManager(  895): Killing 8104:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Launcher( 1584): Deferring update until onResume
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1430): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1430): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1430): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1430): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1430): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1430): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1430): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1430): run()
I/StatsUtilsManager( 1430): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1430): shouldRecordStats() = Too Soon
,I/art     (  895): Explicit concurrent mark sweep GC freed 6130(310KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.575ms total 204.503ms
,W/libprocessgroup(  895): failed to open /acct/uid_10039/pid_8104/cgroup.procs: No such file or directory
,D/AndroidRuntime( 8303): Shutting down VM
,W/ContextImpl( 8358): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6399): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6399): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6399): Reading stored module config
,D/ChimeraCfgMgr( 6399): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6399): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 6399): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6399): App measurement is starting up, version: 8489
I/GMPM-SVC( 6399): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1726): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  895): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8391 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 6399): doRemovePackageData com.test.thalitest
,D/gH_CompatibleDatabase( 6399): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6399): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,W/Launcher( 1584): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1b35f3f new=com.google.android.velvet.VelvetApplication@1b35f3f
,E/SQLiteLog( 1584): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,E/SQLiteLog( 6399): (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 6399): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,--------- beginning of crash
E/AndroidRuntime( 6399): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6399): Process: com.google.android.gms, PID: 6399
E/AndroidRuntime( 6399): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6399): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6399): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 6399): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6399): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6399): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 6399): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6399): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6399): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6399): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6399): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  895): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8412 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/SQLiteLog( 6399): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ChimeraCfgMgr( 6399): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6399): Module APK com.google.android.play.games already loaded
I/Process ( 6399): Sending signal. PID: 6399 SIG: 9
,E/DropBoxManagerService(  895): Can't write: system_app_crash
E/DropBoxManagerService(  895): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  895): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  895): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  895): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  895): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  895): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  895): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  895): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  895): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  895): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  895): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  895): 	... 5 more
,D/WifiService(  895): Client connection lost with reason: 4
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
