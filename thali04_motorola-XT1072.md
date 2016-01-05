#### Test 549702617d40def_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
D/AndroidRuntime( 6422): 
D/AndroidRuntime( 6422): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6422): CheckJNI is OFF
D/AndroidRuntime( 6422): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6441 uid=10409 gids={50409, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6422): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6441): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6441): Time to load native libraries: 2 ms (timestamps 7569-7571)
I/LibraryLoader( 6441): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6441): Binding Chromium to main looper Looper (main, tid 1) {10229e89}
I/LibraryLoader( 6441): Expected native library version number "",actual native library version number ""
I/chromium( 6441): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6441): Initializing chromium process, singleProcess=true
,W/art     ( 6441): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6441): ApplicationContext is null in ApplicationStatus
,W/chromium( 6441): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6441): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6441): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6441): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6441): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6441): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6441): Local Branch: 
I/Adreno-EGL( 6441): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6441): Local Patches: NONE
I/Adreno-EGL( 6441): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12e0f452:true
W/ActivityManager(  881): Activity pause timeout for ActivityRecord{1c42f38f u0 com.test.thalitest/.MainActivity t3}
W/art     ( 6441): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6441): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6441): CordovaWebView is running on device made by: motorola
W/art     ( 6441): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6441): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6441): Render dirty regions requested: true
D/Atlas   ( 6441): Validating map...
W/chromium( 6441): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6441): Initialized EGL, version 1.4
D/OpenGLRenderer( 6441): Enabling debug mode 0
I/Keyboard.Facilitator( 1419): onFinishInput()
I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1008
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +927ms (total +1s8ms)
W/IInputConnectionWrapper( 6441): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6441): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6441): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6441): Cannot call determinedVisibility() - never saw a connection for the pid: 6441
,D/JsMessageQueue( 6441): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6441): JniHelper::setJavaVM(0xb780e310), pthread_self() = -1212548856
,D/JX-Cordova( 6441): jxcore cordova android initializing
,W/jxcore-log( 6441): Initializing JXcore engine
W/jxcore-log( 6441): JXcore engine is ready
,W/jxcore-log( 6441): Starting JXcore engine
,W/.test.thalitest( 6441): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10409 path="socket:[7337]" dev="sockfs" ino=7337 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6441): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10409 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6441): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10409 path="socket:[7567]" dev="sockfs" ino=7567 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6441): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10409 path="socket:[27019]" dev="sockfs" ino=27019 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6441): Platform android
W/jxcore-log( 6441): 
W/jxcore-log( 6441): Process ARCH arm
W/jxcore-log( 6441): 
,I/jxcore-log( 6441): JXcore Cordova bridge is ready!
I/jxcore-log( 6441): 
,W/jxcore-log( 6441): JXcore engine is started
I/Choreographer( 6441): Skipped 168 frames!  The application may be doing too much work on its main thread.
I/chromium( 6441): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6441): Toggling radios to true
I/jxcore-log( 6441): 
,D/BluetoothAdapter( 6441): enable(): BT is already enabled..!
,D/WifiService(  881): New client listening to asynchronous messages
,D/WifiService(  881): setWifiEnabled: true pid=6441, uid=10409
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6441): Radios toggled
I/jxcore-log( 6441): 
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  290): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  290):  STA Disconnected !!
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
,I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  290): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  290): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  881): InitialState.processMessage what=4
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881):  0
I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  290): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
,D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  288): Clearing all IP addresses on wlan0
D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 21
D/TCMD    (  465): Listening for incoming client connection request
,V/NativeCrypto( 1706): Read error: ssl=0xb7bb8ca8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1706): SSL shutdown failed: ssl=0xb7bb8ca8: I/O error during system call, Broken pipe
,D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiMetrics(  881): connected time updated 121114
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6519 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  881): Start Disconnecting Watchdog 1
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  881): ConnectModeState: Network connection lost 
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  288): Clearing all IP addresses on wlan0
D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524292
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6519): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6547 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6195:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  290): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/wpa_supplicant( 1433): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  290): Event received = Trying to associate with
D/WifiMonitor(  881): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1433): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiStateMachine(  881): [1,451,956,932,843 ms] noteScanEnd no scan source
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_6195/cgroup.procs: No such file or directory
E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@313ff22d sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6547): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1706): Scheduling Phenotype for one-off execution 3660 seconds from now (1451956932920)
,D/TCMD    (  465): NL - Read 312 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 192 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
I/wpa_supplicant( 1433): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  290): Event received = Associated with c0:ff:d4
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1433): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  290): Event received = WPA: Key negotiation com
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  290): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  290):  STA Connected !!
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/MDMCTBK (  290): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  290): get_freq !!, resp=2412
I/MDMCTBK (  290): get_freq !!, Strip data
I/MDMCTBK (  290): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  290): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  290): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  290): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195758120
I/MDMCTBK (  290): return from set_get_from_wpa_supplicant
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  290): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  290): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  290): , reply_len: 3, ret: 0
E/MDMCTBK (  290): MdmCutbackHndler, resp=OK
E/MDMCTBK (  290): 
,D/MDMCTBK (  290): wifi_set_tx_pwr: Exit
,D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  881): Network connection established
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  881): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  881): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  881): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
,E/WifiStateMachine(  881): Start Dhcp Watchdog 2
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend false
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29ce31fc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29ce31fc target=com.android.internal.util.StateMachine$SmHandler }
,I/art     (  881): Explicit concurrent mark sweep GC freed 61643(2MB) AllocSpace objects, 3(227KB) LOS objects, 33% free, 20MB/30MB, paused 6.540ms total 158.100ms
,D/GetConfigurationSnapshotOperation( 1706): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1706): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1706): Using platform SSLCertificateSocketFactory
,I/Babel_SMS( 6547): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6547): MmsConfig.loadMmsSettings
I/Babel_SMS( 6547): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6547): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6547): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6547): MmsConfig.loadFromResources
,E/Babel_SMS( 6547): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6547): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/Uploader( 1706): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/DHCPCD  ( 6583): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6583): version 5.5.6 starting
,E/DHCPCD  ( 6583): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6583): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6583): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6583): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6583): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6583): wlan0: sending REQUEST (xid 0x7f7c0855), next in 3.03 seconds
,W/Settings( 6547): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6547): startup - clean
,I/Babel   ( 6547): deleted: false for 0
,I/DHCPCD  ( 6583): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6583): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6583): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6583): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6583): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6583): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 20
D/TCMD    (  465): Listening for incoming client connection request
D/DHCPCD  ( 6583): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6547): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 6547): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6547): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6547): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  881): Killing 6227:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): WifiStateMachine DHCP successful
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  881): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6227/cgroup.procs: No such file or directory
,I/vclib   ( 6547): onServiceConnected
,W/Babel   ( 6547): Attempted to change video mute state without an active call.
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  881): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  881): Adding iface wlan0 to network 101
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  881): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  881): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  881): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
E/WifiStateMachine(  881): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  881): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  881): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  881): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881):    accepting network in place of null
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/CSLegacyTypeTracker(  881): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  881): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 01:22:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451956934080], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451956934059]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1535): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  881): send {25b942e9, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {c8f770c, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  881): done {c8f770c, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6ms]
,V/AlarmManager(  881): done {25b942e9, *alarm*:android.intent.action.TIME_TICK} [36ms]
,D/ConnectivityService(  881): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1468): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  881): MasterInitialState.processMessage what=3
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6641 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1468): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1468): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2609): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2609): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2609): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2609): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2609): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2609): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2609): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2609): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2609): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2609): [debug] > CusSM.onRadioDown
,I/MusicStore( 6641): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6641): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6641): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6641): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6641): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6641): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6641): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6641): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6641): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17f08875: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6641): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6641): GMSCore installation verified
,I/ConfigStore( 6641): Config Database version: 1
,I/MediaRouter( 6641): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6641): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6641): type=WIFI subType= reason=null isConnected=true
,E/global frequency( 2609): no tags to log
,D/Checkin ( 2609): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/NetworkMonitor( 6641): type=WIFI subType= reason=null isConnected=true
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6684 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.587ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.973ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.419ms
,I/GHttpClientFactory( 6641): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6641): Using platform SSLCertificateSocketFactory
,I/art     ( 2609): Explicit concurrent mark sweep GC freed 22006(1236KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/18MB, paused 1.398ms total 93.972ms
,I/ActivityManager(  881): Killing 6054:android.process.acore/u0a7 (adj 15): empty #7
,V/Mms     ( 6684): mnc/mcc: 
,V/Mms     ( 6684): tag: int value: recipientLimit - 20
,V/Mms     ( 6684): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6684): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6684): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6684): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6684): tag: bool value: enableGroupMms - false
V/Mms     ( 6684):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2609): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6054/cgroup.procs: No such file or directory
,I/art     ( 1468): Explicit concurrent mark sweep GC freed 55525(3MB) AllocSpace objects, 37(1244KB) LOS objects, 40% free, 7MB/12MB, paused 793us total 49.033ms
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6716 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  881): Explicit concurrent mark sweep GC freed 26227(1298KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.631ms total 127.629ms
,I/ActivityManager(  881): Killing 6133:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6716): Register our PhoneStateListener
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2609): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_6133/cgroup.procs: No such file or directory
,V/AlarmManager(  881): send {a3c492a, *walarm*:com.google.android.intent.action.SEND_IDLE}
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1468): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1468): now: 196613 ,futureTime: 86475624
D/Central_PollingManager( 1468): Polling alarm set to expire at: 86475624 Current Time: 196613
,I/NetworkMonitor( 6641): type=WIFI subType= reason=null isConnected=true
,D/MobileConnectivityChangeReceiver( 6716): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6716): onReceive CONNECTIVITY_CHANGE networkType=1
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  881): Killing 6519:com.motorola.context/u0a8 (adj 15): empty #7
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BSUtils ( 2609): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2609): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6519/cgroup.procs: No such file or directory
,D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2609): now: 196853 ,futureTime: 9223372036854775807
D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2609): now: 196853 ,futureTime: 9223372036854775807
D/PollingManager( 2609): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2609): now: 196853 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2609): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BSUtils ( 2609): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/OtaApp  ( 2609): [debug] > PollingManagerService, now: 196856 ,futureTime: 53523102
,D/OtaApp  ( 2609): [debug] > Polling alarm set to expire at: 53523102 Current Time: 196857
,I/global frequency( 2609): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2609): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2609): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2609): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2609): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/CheckinService( 6295): Checkin interval check for package: unspecified last checkin: 1451956855112 min interval config: 0 actual interval: 82227
I/art     ( 1468): Explicit concurrent mark sweep GC freed 4527(195KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 598us total 28.454ms
,D/MMApiProvisionService( 2609): isDeviceProvisioned: deviceId = 2072049230914535424
,I/CheckinService( 6295): Disabling old GoogleServicesFramework version
,D/CCE     ( 2609): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2609): createDeviceIdOrLogin update_device
,D/Checkin ( 2609): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2609): Not proxy app, so login/provision not allowed
,I/iu.SyncManager( 6295): SYNC; picasa accounts
,I/CheckinService( 6295): Checking schedule, now: 1451956937386 next: 1451956885094
I/CheckinService( 6295): active receiver: enabled
,D/MMApiProvisionService( 2609): isDeviceProvisioned: deviceId = 2072049230914535424
,D/NetworkLogImpl( 6295): Loaded NetworkSpeedPredictor
,I/CheckinService( 6295): Preparing to send checkin request
,I/EventLogService( 6295): Accumulating logs since 1451956851955
,I/iu.Environment( 6295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/CCE     ( 2609): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2609): createDeviceIdOrLogin update_device
,D/Checkin ( 2609): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2609): isDeviceProvisioned: deviceId = 2072049230914535424
,I/iu.UploadsManager( 6295): num queued entries: 0
D/MMApiProvisionService( 2609): set mOutstandingReq to true.
I/ Nonce  ( 2609):  Nonce getNonce 
I/ Nonce  ( 2609):  Nonce Request 
I/ Nonce  ( 2609):  Nonce execute Request 
,I/iu.UploadsManager( 6295): num updated entries: 0
I/iu.SyncManager( 6295): NEXT; no task
D/MMApiWebService( 2609): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2609): isDeviceProvisioned: deviceId = 2072049230914535424
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6744 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/CCE     ( 2609): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2609): createDeviceIdOrLogin update_device
,D/Checkin ( 2609): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2609): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2609): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2609): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2609): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2609): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2609): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2609): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2609): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2609): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2609): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2609): generating token using payload instead of using session token
,I/art     ( 2609): Explicit concurrent mark sweep GC freed 10935(638KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.108ms total 65.133ms
,D/ Nonce  ( 2609):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2609): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2609): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinRequestBuilder( 6295): Checkin reason type: 8 attempt count: 1
,D/WifiService(  881): New client listening to asynchronous messages
,E/ActivityThread( 6295): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  881): Explicit concurrent mark sweep GC freed 10554(501KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 7.235ms total 122.440ms
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6768 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 6547): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6787 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6787): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6787): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6787): VM with version 2.1.0 has multidex support
,I/MultiDex( 6787): install
I/MultiDex( 6787): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6787): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6787): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/System  ( 6787): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@357ced52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6787): Installed default security provider GmsCore_OpenSSL
W/ContextImpl( 6768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6768): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6768):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6768):   adb logcat -s GAv4
,I/ Nonce  ( 2609):  Nonce Reponse 
D/        ( 2609): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"f5ed71bb-4d4d-4afb-a186-300b4454e0f2"}
D/MMApiWSBase( 2609): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2609):  Nonce Handle Reponse 
D/MMApiProvisionService( 2609): mOutstandingReq set to false
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 6768): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 6787): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6787): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/ContextImpl( 6768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6768): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6768): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 6787): Install completed successfully. count=14 extracted=0
,D/MMApiProvisionService( 2609):  pTime 1451923699777 sExp 172742 cTime 1451956938679 tTime 1452096441777
D/MMApiProvisionService( 2609):  No login Required 
,I/art     ( 6263): Explicit concurrent mark sweep GC freed 1946(85KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 365us total 24.780ms
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
,I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f73000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f73000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb544e960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7e62120, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7d36648, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e69e40, idLength=0xbed562b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=2335692992
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d71108
D/DrmWidevineDash(  294): message_length=1591, signature=0xb7d51820, signature_length=3201655444
,I/WebViewFactory( 6768): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6768): Time to load native libraries: 1 ms (timestamps 8573-8574)
I/LibraryLoader( 6768): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6768): Binding Chromium to main looper Looper (main, tid 1) {21774f02}
I/LibraryLoader( 6768): Expected native library version number "",actual native library version number ""
I/chromium( 6768): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/DataUsage( 2609): invalid counter update blocked: 'err' by 0
D/Checkin ( 2609): publish the event [tag = MOT_CCE event name = LOG]
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/BrowserStartupController( 6768): Initializing chromium process, singleProcess=true
,W/art     ( 6768): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6768): ApplicationContext is null in ApplicationStatus
,W/chromium( 6768): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6768): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6768): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6768): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6768): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6768): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6768): Local Branch: 
I/Adreno-EGL( 6768): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6768): Local Patches: NONE
I/Adreno-EGL( 6768): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 6846): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/AudioManagerAndroid( 6768): Requires BLUETOOTH permission
,I/NSApplication( 6768): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6864 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6641:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/dex2oat ( 6846): dex2oat took 90.113ms (threads: 4)
,I/Adreno-EGL( 6787): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6787): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6787): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6787): Local Branch: 
I/Adreno-EGL( 6787): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6787): Local Patches: NONE
I/Adreno-EGL( 6787): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6787): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6787): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6787): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6787): Local Branch: 
I/Adreno-EGL( 6787): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6787): Local Patches: NONE
I/Adreno-EGL( 6787): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6641/cgroup.procs: No such file or directory
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6890 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6684:com.android.mms/u0a23 (adj 15): empty #7
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f73000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f73000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbed564e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7e623b8, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7d36648, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e69e80, idLength=0xb554e730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=2135772267
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d71108
D/DrmWidevineDash(  294): message_length=1626, signature=0xb7d54570, signature_length=3042240276
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6684/cgroup.procs: No such file or directory
,W/ResourcesManager( 6890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6915 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6943 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6744:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 6915): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 6716:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6744/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6716/cgroup.procs: No such file or directory
,I/MusicStore( 6943): Database version: 120
,I/Adreno-EGL( 6787): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6787): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6787): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6787): Local Branch: 
I/Adreno-EGL( 6787): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6787): Local Patches: NONE
I/Adreno-EGL( 6787): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6943): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/Adreno-EGL( 6787): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6787): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6787): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6787): Local Branch: 
I/Adreno-EGL( 6787): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6787): Local Patches: NONE
I/Adreno-EGL( 6787): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6943): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6943): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6943): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6943): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6943): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6943): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6943): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17f08875: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6943): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6943): GMSCore installation verified
,I/ConfigStore( 6943): Config Database version: 1
,W/art     ( 6943): Suspending all threads took: 9.152ms
,I/MediaRouter( 6943): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6943): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6943): type=WIFI subType= reason=null isConnected=true
,I/CheckinRequestBuilder( 6295): Classify the device as Phone.
,I/NetworkMonitor( 6943): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6984 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6943): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6943): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6547:com.google.android.talk/u0a70 (adj 15): empty #7
,I/CheckinTask( 6295): Sending checkin request (9559 bytes)
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6547/cgroup.procs: No such file or directory
,V/Mms     ( 6984): mnc/mcc: 
,V/Mms     ( 6984): tag: int value: recipientLimit - 20
V/Mms     ( 6984): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6984): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6984): tag: int value: maxSubjectLength - 80
V/Mms     ( 6984): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6984): tag: bool value: enableGroupMms - false
,V/Mms     ( 6984):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  881): Explicit concurrent mark sweep GC freed 9594(468KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 3.409ms total 114.626ms
,W/ResourcesManager( 6984): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7023 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6768:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7023): Register our PhoneStateListener
,I/CheckinRequestBuilder( 6295): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_6768/cgroup.procs: No such file or directory
,E/ActivityThread( 6295): Failed to find provider info for com.google.android.wearable.settings
,D/MobileConnectivityChangeReceiver( 7023): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7023): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6295): Checkin interval check for package: unspecified last checkin: 1451956855112 min interval config: 0 actual interval: 87329
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7048 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.341ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.062ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.442ms
,I/ActivityManager(  881): Killing 6864:com.android.chrome/u0a52 (adj 15): empty #7
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310731, SEQNUM=4454, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-23537, POWER_SUPPLY_CHARGE_COUNTER=-649, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6864/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/CheckinRequestBuilder( 6295): Classify the device as Phone.
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7072 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6915:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6915/cgroup.procs: No such file or directory
,I/CheckinTask( 6295): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6295): Checking schedule, now: 1451956943105 next: 1452558080098
I/CheckinService( 6295): active receiver: disabled
,W/ResourcesManager( 7072): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinService( 6295): Checking schedule, now: 1451956943140 next: 1452558080098
I/CheckinService( 6295): active receiver: disabled
,D/CheckinService( 6295): Recording last checkin time for package unspecified as 1451956943144
,I/ActivityManager(  881): Killing 6943:com.google.android.music:main/u0a80 (adj 13): empty #7
,I/ActivityManager(  881): Killing 6890:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6943/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6890/cgroup.procs: No such file or directory
,I/Babel_SMS( 7072): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7072): MmsConfig.loadMmsSettings
I/Babel_SMS( 7072): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7072): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7072): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7072): MmsConfig.loadFromResources
E/Babel_SMS( 7072): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7072): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7072): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7072): startup - clean
,I/Babel   ( 7072): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7107 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7072): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7072): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7072): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7072): onServiceConnected
W/Babel   ( 7072): Attempted to change video mute state without an active call.
,I/GAv4    ( 7107): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7107):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7107):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7107): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7107): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7107): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7072): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 6984:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7107): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7107): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7107): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7107): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6984/cgroup.procs: No such file or directory
,I/WebViewFactory( 7107): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7107): Time to load native libraries: 1 ms (timestamps 4010-4011)
I/LibraryLoader( 7107): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7107): Binding Chromium to main looper Looper (main, tid 1) {21774f02}
I/LibraryLoader( 7107): Expected native library version number "",actual native library version number ""
I/chromium( 7107): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7107): Initializing chromium process, singleProcess=true
W/art     ( 7107): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7107): ApplicationContext is null in ApplicationStatus
,W/chromium( 7107): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7107): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7107): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7107): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7107): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7107): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7107): Local Branch: 
I/Adreno-EGL( 7107): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7107): Local Patches: NONE
I/Adreno-EGL( 7107): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7107): Requires BLUETOOTH permission
,I/NSApplication( 7107): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7173 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7023:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/jxcore-log( 6441): Test app app.js loaded
I/jxcore-log( 6441): 
,I/chromium( 6441): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7023/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7192 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7048:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7048/cgroup.procs: No such file or directory
,W/ResourcesManager( 7192): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7215 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7107:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7215): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 7072:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2609): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7072/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7107/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2609): bindWebServices(): registering our AIDL callback...
I/SundryService( 2609): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2609): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2609): onServiceConnected()
D/GetNotificationsWS( 2609): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2609): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2609): started with background data enabled, making sure notification mechanism is enabled
,V/AlarmManager(  881): done {a3c492a, *walarm*:com.google.android.intent.action.SEND_IDLE} [8541ms]
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7244 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7244): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7244): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7244): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7244): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7244): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7244): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7244): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7244): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7244): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17f08875: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7244): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7244): GMSCore installation verified
,I/ConfigStore( 7244): Config Database version: 1
,I/MediaRouter( 7244): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7244): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7244): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7244): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7277 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  881): Explicit concurrent mark sweep GC freed 12055(634KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.655ms total 142.492ms
,I/GHttpClientFactory( 7244): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7244): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 7173:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7277): mnc/mcc: 
,V/Mms     ( 7277): tag: int value: recipientLimit - 20
V/Mms     ( 7277): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7277): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7277): tag: int value: maxSubjectLength - 80
V/Mms     ( 7277): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7277): tag: bool value: enableGroupMms - false
V/Mms     ( 7277):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7173/cgroup.procs: No such file or directory
,W/ResourcesManager( 7277): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7312 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7192:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7192/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7312): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7312): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7312): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 7215:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7215/cgroup.procs: No such file or directory
,I/CheckinService( 6295): Checkin interval check for package: unspecified last checkin: 1451956943144 min interval config: 0 actual interval: 3240
,I/CheckinService( 6295): Checking schedule, now: 1451956946391 next: 1451956973098
I/CheckinService( 6295): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7335 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7355 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7244:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_7244/cgroup.procs: No such file or directory
,W/ResourcesManager( 7355): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7355): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7355): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7355): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7355): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7355): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7355): MmsConfig.loadFromResources
,E/Babel_SMS( 7355): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7355): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7355): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7355): startup - clean
,I/Babel   ( 7355): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7386 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/art     (  307): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 22.974ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.268ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.020ms
,W/VideoCapabilities( 7355): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7355): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7355): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7355): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7355): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7355): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7355): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7355): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7355): onServiceConnected
W/Babel   ( 7355): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7386): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7386): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7386):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7386):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7386): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7355): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 7277:com.android.mms/u0a23 (adj 15): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7386): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7386): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_7277/cgroup.procs: No such file or directory
,W/GAv4    ( 7386): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7386): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,W/GAv4    ( 7386): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3662bd16
,I/GCoreNlp( 1706): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/WebViewFactory( 7386): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7386): Time to load native libraries: 1 ms (timestamps 7308-7309)
,I/LibraryLoader( 7386): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7386): Binding Chromium to main looper Looper (main, tid 1) {21774f02}
,I/LibraryLoader( 7386): Expected native library version number "",actual native library version number ""
,I/chromium( 7386): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7386): Initializing chromium process, singleProcess=true
,W/art     ( 7386): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7386): ApplicationContext is null in ApplicationStatus
,W/chromium( 7386): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7386): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7386): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7386): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7386): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7386): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7386): Local Branch: 
I/Adreno-EGL( 7386): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7386): Local Patches: NONE
I/Adreno-EGL( 7386): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7386): Requires BLUETOOTH permission
,I/NSApplication( 7386): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7457 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6787:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_6787/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7476 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7312:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7312/cgroup.procs: No such file or directory
,W/ResourcesManager( 7476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7499 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7355:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7335:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 7499): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7355/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2609): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7335/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2609): bindWebServices(): registering our AIDL callback...
I/SundryService( 2609): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2609): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2609): onServiceConnected()
D/GetNotificationsWS( 2609): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2609): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2609): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2609): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2609): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2609): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  881): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7529 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2609): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2609): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2609): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2609): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2609): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2609): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2609): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2609): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2609): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6441): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1419): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,163
,D/WearableService( 1706): callingUid 10016, callindPid: 1706
,D/LocationInitializer( 6295): Restart initialization of location
,E/MDM     ( 1706): [171] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1706): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  881): Explicit concurrent mark sweep GC freed 19112(944KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.598ms total 126.242ms
,W/GCoreFlp( 1706): No location to return for getLastLocation()
W/FusedLocationProvider( 1706): location=null
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7564 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7564): Register our PhoneStateListener
,V/SetupWizard( 7564): Connected to Gservices successfully
,I/ActivityManager(  881): Killing 7386:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7386/cgroup.procs: No such file or directory
,D/GCM     ( 1706): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1706): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7587 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7609 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7626 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7457:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7476:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7457/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7476/cgroup.procs: No such file or directory
,W/ResourcesManager( 7626): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7626): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7626): MmsConfig.loadMmsSettings
I/Babel_SMS( 7626): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7626): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7626): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7626): MmsConfig.loadFromResources
,E/Babel_SMS( 7626): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7626): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7626): startup - clean
,I/Babel   ( 7626): deleted: false for 0
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7663 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7626): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7626): Unsupported mime video/mpeg2
,W/asset   ( 7663): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7663): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7663): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7663): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7626): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6295): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 7587): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2067decb new=com.google.android.velvet.VelvetApplication@2067decb
,I/PackageBroadcastService( 6295): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7689 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7626): onServiceConnected
W/Babel   ( 7626): Attempted to change video mute state without an active call.
,I/Icing   ( 6295): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7626): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7626): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7689): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/art     ( 7626): Suspending all threads took: 8.545ms
,I/UpdateIcingCorporaServi( 7587): UpdateCorporaTask done [took 202 ms] updated apps [took 201 ms] 
,I/ActivityManager(  881): Killing 7564:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,V/JNIHelp ( 7626): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7626): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7626): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7564/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7726 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 22.736ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.034ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.267ms
,I/ActivityManager(  881): Killing 7529:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7529/cgroup.procs: No such file or directory
,I/art     ( 6263): Explicit concurrent mark sweep GC freed 1948(73KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 341us total 22.423ms
,D/Finsky  ( 7726): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7726): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7726): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7726): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7726): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7726): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7726): Skipping gmscore version check
,D/Finsky  ( 7726): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7726): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 7609:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7609/cgroup.procs: No such file or directory
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6295): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6295): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6295): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  881): Killing 7663:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_7663/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7587:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7587/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/CheckinService( 6295): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311214, SEQNUM=4481, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-783, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1706): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {25b942e9, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {4084140, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  881): send {2418d094, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  881): done {4084140, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [22ms]
,V/AlarmManager(  881): done {2418d094, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [32ms]
,I/CheckinService( 6295): Checkin interval check for package: unspecified last checkin: 1451956943144 min interval config: 0 actual interval: 44270
,V/AlarmManager(  881): done {25b942e9, *alarm*:android.intent.action.TIME_TICK} [57ms]
,I/CheckinService( 6295): Checking schedule, now: 1451956987438 next: 1451956973098
I/CheckinService( 6295): active receiver: enabled
,I/CheckinService( 6295): Preparing to send checkin request
I/EventLogService( 6295): Accumulating logs since 1451956937642
,I/CheckinRequestBuilder( 6295): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6295): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7799 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7799): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7799): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7799): VM with version 2.1.0 has multidex support
I/MultiDex( 7799): install
I/MultiDex( 7799): VM has multidex support, MultiDex support library is disabled.
,I/art     (  881): Explicit concurrent mark sweep GC freed 14942(745KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.647ms total 120.431ms
,V/JNIHelp ( 7799): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7799): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7799): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@357ced52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7799): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1706): callingUid 10016, callindPid: 1706
,E/MDM     ( 1706): [209] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1706): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6295): Restart initialization of location
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1706): No location to return for getLastLocation()
,W/FusedLocationProvider( 1706): location=null
,I/art     ( 7799): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7799): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7799): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
,I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f73000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f73000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbed564e0
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7e62828, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7d36648, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e69e60, idLength=0xb1264730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=685829331
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d71108
D/DrmWidevineDash(  294): message_length=1591, signature=0xb7d54830, signature_length=2972075796
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7843): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7843): dex2oat took 62.518ms (threads: 4)
,I/Adreno-EGL( 7799): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7799): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7799): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7799): Local Branch: 
I/Adreno-EGL( 7799): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7799): Local Patches: NONE
I/Adreno-EGL( 7799): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7799): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7799): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7799): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7799): Local Branch: 
I/Adreno-EGL( 7799): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7799): Local Patches: NONE
I/Adreno-EGL( 7799): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f73000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f73000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb1364960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7e62988, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7d36648, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e69e80, idLength=0xb1264730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3032290466
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d71108
D/DrmWidevineDash(  294): message_length=1626, signature=0xb7d546c8, signature_length=2972075796
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7799): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7799): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7799): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7799): Local Branch: 
I/Adreno-EGL( 7799): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7799): Local Patches: NONE
I/Adreno-EGL( 7799): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7799): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7799): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7799): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7799): Local Branch: 
I/Adreno-EGL( 7799): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7799): Local Patches: NONE
I/Adreno-EGL( 7799): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6295): Classify the device as Phone.
,I/CheckinTask( 6295): Sending checkin request (9560 bytes)
,I/CheckinRequestBuilder( 6295): Checkin reason type: 8 attempt count: 1
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,E/ActivityThread( 6295): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6295): Classify the device as Phone.
,I/CheckinTask( 6295): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6295): Checking schedule, now: 1451956991436 next: 1452558128432
I/CheckinService( 6295): active receiver: disabled
,D/CheckinService( 6295): Recording last checkin time for package unspecified as 1451956991453
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7879 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7879): Register our PhoneStateListener
,V/SetupWizard( 7879): Connected to Gservices successfully
,D/GCM     ( 1706): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Killing 7499:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  881): Killing 7626:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7499/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7626/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7909 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@7fcafb7
,I/GCoreNlp( 1706): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/art     ( 1706): Explicit concurrent mark sweep GC freed 97235(5MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 15MB/25MB, paused 1.240ms total 124.330ms
,E/DataBuffer( 1706): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b41b811)
E/DataBuffer( 1706): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f36bd76)
E/DataBuffer( 1706): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@274ccf77)
E/DataBuffer( 1706): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ff4c7e4)
E/DataBuffer( 1706): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e78c44d)
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7947 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7953 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7689:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7689/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7726:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_7726/cgroup.procs: No such file or directory
,W/ResourcesManager( 7953): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7953): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7953): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7953): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7953): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7953): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7953): MmsConfig.loadFromResources
,E/Babel_SMS( 7953): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7953): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7953): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7953): startup - clean
,I/Babel   ( 7953): deleted: false for 0
,I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7996 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 7953): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7953): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7953): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7953): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7953): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7953): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7953): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7953): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8021 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7879:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 7996): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7879/cgroup.procs: No such file or directory
,I/vclib   ( 7953): onServiceConnected
,W/Babel   ( 7953): Attempted to change video mute state without an active call.
,W/asset   ( 8021): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8021): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8021): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8021): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7953): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7953): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6295): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6295): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2067decb new=com.google.android.velvet.VelvetApplication@2067decb
I/UpdateIcingCorporaServi( 7909): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,V/JNIHelp ( 7953): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Icing   ( 6295): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8048 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 7953): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7953): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 8048): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7909): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
,I/art     (  881): Explicit concurrent mark sweep GC freed 17860(927KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.806ms total 115.933ms
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8079 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7799:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_7799/cgroup.procs: No such file or directory
,D/Finsky  ( 8079): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8079): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8079): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8079): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8079): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8079): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8079): Skipping gmscore version check
,D/Finsky  ( 8079): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8079): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 7947:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7947/cgroup.procs: No such file or directory
,I/Icing   ( 6295): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6295): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  881): Killing 8021:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_8021/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7953:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7953/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1419): run()
,I/Keyboard.Facilitator( 1419): flushDynamicLanguageModels()
,I/ConfigService( 1706): onCreate
,I/ConfigService( 1706): onDestroy
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310201, SEQNUM=4509, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16326, POWER_SUPPLY_CHARGE_COUNTER=-968, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=238, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312153, SEQNUM=4515, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-1643, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  881): send {25b942e9, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {384f7f7, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  881): send {33561b7c, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8160 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
V/AlarmManager(  881): done {384f7f7, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [64ms]
,V/AlarmManager(  881): done {25b942e9, *alarm*:android.intent.action.TIME_TICK} [95ms]
,I/GAv4    ( 8160): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8160):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8160):   adb logcat -s GAv4
,W/GAv4    ( 8160): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8160): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8160): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  881): done {33561b7c, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [291ms]
I/ActivityManager(  881): Killing 7909:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7909/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=230, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311461, SEQNUM=4521, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  881): send {25b942e9, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {15f1ac05, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  881): done {25b942e9, *alarm*:android.intent.action.TIME_TICK} [44ms]
,V/AlarmManager(  881): done {15f1ac05, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [84ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=229, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311457, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2117, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=228, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310869, SEQNUM=4526, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=228, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310578, SEQNUM=4528, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=228, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311159, SEQNUM=4530, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=228, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311738, SEQNUM=4532, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=227, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311738, SEQNUM=4533, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  881): send {25b942e9, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {b2df45a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  881): done {b2df45a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [20ms]
,V/AlarmManager(  881): done {25b942e9, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=227, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310543, SEQNUM=4535, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5446, POWER_SUPPLY_CHARGE_COUNTER=13, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,V/AlarmManager(  881): send {384f7f7, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,I/ProcessStatsService(  881): Prepared write state in 27ms
,V/AlarmManager(  881): send {25b942e9, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {5f3daf, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  881): send {23a77368, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  881): send {1de60381, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  881): done {384f7f7, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [44ms]
,I/ProcessStatsService(  881): Prepared write state in 13ms
,V/AlarmManager(  881): done {5f3daf, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [89ms]
,V/AlarmManager(  881): done {23a77368, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [106ms]
,V/AlarmManager(  881): done {25b942e9, *alarm*:android.intent.action.TIME_TICK} [109ms]
,V/AlarmManager(  881): done {1de60381, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [113ms]
,I/EventLogService( 6295): Aggregate from 1451956987461 (log), 1451956498743 (data)
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  881): Pruning old procstats: /data/system/procstats/state-2016-01-04-01-08-22.bin
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,V/AlarmManager(  881): send {25b942e9, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {15f1ac05, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  881): done {15f1ac05, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [22ms]
,V/AlarmManager(  881): done {25b942e9, *alarm*:android.intent.action.TIME_TICK} [58ms]
,V/AlarmManager(  881): send {2357444, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  881): send {2ac7692d, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  881): send {3ec1ae62, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  881): done {2357444, *walarm*:com.motorola.ccc.cce.alarmintent} [89ms]
,V/AlarmManager(  881): done {2ac7692d, *walarm*:com.motorola.ccc.cce.alarmintent} [105ms]
,V/AlarmManager(  881): done {3ec1ae62, *walarm*:com.motorola.ccc.cce.alarmintent} [123ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:25000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8253): 
D/AndroidRuntime( 8253): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8253): CheckJNI is OFF
D/AndroidRuntime( 8253): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10409 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6441:com.test.thalitest/u0a409 (adj 9): stop com.test.thalitest
W/PackageSettings(  881): Skipping PackageSetting{18adcd86 com.example.hello/10406} due to missing metadata
I/WindowState(  881): WIN DEATH: Window{f6b1602 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  881): Client connection lost with reason: 4
I/ActivityManager(  881):   Force finishing activity ActivityRecord{1c42f38f u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  881): Spurious death for ProcessRecord{3d654bf3 6441:com.test.thalitest/u0a409}, curProc for 6441: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10409 user=0: pkg removed
I/ActivityManager(  881):   Force finishing activity ActivityRecord{1c42f38f u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{1c42f38f u0 com.test.thalitest/.MainActivity t3 f}
I/art     ( 3025): Explicit concurrent mark sweep GC freed 11842(2MB) AllocSpace objects, 35(560KB) LOS objects, 40% free, 7MB/12MB, paused 928us total 42.548ms
I/art     ( 1572): Explicit concurrent mark sweep GC freed 5100(315KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 484us total 69.190ms
I/Keyboard.Facilitator( 1419): resetDictionaries() : en_US
W/GeofencerStateMachine( 1706): Ignoring removeGeofence because network location is disabled.
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1419): run()
D/VoicemailCleanupService( 7996): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1419): createOrResetDecoder
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8284 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 23.170ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.570ms
I/art     (  881): Explicit concurrent mark sweep GC freed 25815(1812KB) AllocSpace objects, 11(261KB) LOS objects, 33% free, 20MB/30MB, paused 2.130ms total 157.248ms
I/art     (  881): WaitForGcToComplete blocked for 106.634ms for cause Explicit
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.288ms
I/ConfigService( 1706): onCreate
W/asset   ( 8284): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8284): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8284): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1419): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1419): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1419): run()
I/StatsUtilsManager( 1419): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1419): shouldRecordStats() = Time to Run
I/PeriodicStatsRecorder( 1419): shouldRecordStats() = Time to Run
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8310 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  881): Killing 8048:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Launcher( 1572): Deferring update until onResume
I/art     (  881): Explicit concurrent mark sweep GC freed 6699(350KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.770ms total 205.559ms
W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_8048/cgroup.procs: No such file or directory
D/AndroidRuntime( 8253): Shutting down VM
W/ContextImpl( 8310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6295): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6295): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6295): Reading stored module config
D/ChimeraCfgMgr( 6295): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6295): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6295): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6295): App measurement is starting up, version: 8489
I/GMPM-SVC( 6295): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1706): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1706): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6295): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6295): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6295): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6295): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6295): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6295): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6295): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6295): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6295): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6295): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6295): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6295): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6295): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8342 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/BaseAppContext( 6295): Using Auth Proxy for data requests.
I/Icing   ( 6295): doRemovePackageData com.test.thalitest
D/ChimeraCfgMgr( 6295): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6295): Module APK com.google.android.play.games already loaded
W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2067decb new=com.google.android.velvet.VelvetApplication@2067decb
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8366 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/BaseAppContext( 6295): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 6295): Using Auth Proxy for data requests.
E/SQLiteDatabase( 6295): Error inserting name=gcoreVersion value=8489236
E/SQLiteDatabase( 6295): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6295): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6295): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 6295): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6295): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6295): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
E/SQLiteDatabase( 6295): 	at android.database.sqlite.SQLiteDatabase.replace(SQLiteDatabase.java:1387)
E/SQLiteDatabase( 6295): 	at com.google.android.gms.people.c.f.a(SourceFile:2539)
E/SQLiteDatabase( 6295): 	at com.google.android.gms.people.c.f.b(SourceFile:2529)
E/SQLiteDatabase( 6295): 	at com.google.android.gms.people.c.f.b(SourceFile:788)
E/SQLiteDatabase( 6295): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 6295): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 6295): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 6295): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 6295): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 6295): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6295): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6295): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6295): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6295): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 6295): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6295): Process: com.google.android.gms, PID: 6295
E/AndroidRuntime( 6295): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6295): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6295): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6295): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6295): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6295): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6295): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6295): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6295): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6295): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6295): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6295): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6295): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6295): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6295): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BaseAppContext( 6295): Using Auth Proxy for data requests.
W/BaseAppContext( 6295): Using Auth Proxy for data requests.
D/ConnectivityService(  881): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  881): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6295): CM callback handler got msg 524290
I/Process ( 6295): Sending signal. PID: 6295 SIG: 9
D/ConnectivityService(  881): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@22706100)
D/WifiService(  881): Client connection lost with reason: 4
D/ConnectivityService(  881): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  881): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  881): Process com.google.android.gms (pid 6295) has died
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1222ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11221ms
E/native  ( 1419): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1419): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1419): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1419): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1419): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1419): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8403 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
