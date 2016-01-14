#### Test 55613145c131883_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6401): 
D/AndroidRuntime( 6401): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6401): CheckJNI is OFF
D/AndroidRuntime( 6401): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6420 uid=10449 gids={50449, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6401): Shutting down VM
V/ActivityManager(  879): Display changed displayId=0
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6420): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6420): Time to load native libraries: 17 ms (timestamps 7417-7434)
I/LibraryLoader( 6420): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6420): Binding Chromium to main looper Looper (main, tid 1) {f630d98}
I/LibraryLoader( 6420): Expected native library version number "",actual native library version number ""
,I/chromium( 6420): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6420): Initializing chromium process, singleProcess=true
W/art     ( 6420): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6420): ApplicationContext is null in ApplicationStatus
,W/chromium( 6420): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6420): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6420): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6420): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6420): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6420): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6420): Local Branch: 
I/Adreno-EGL( 6420): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6420): Local Patches: NONE
I/Adreno-EGL( 6420): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29f744ae:true
,W/ActivityManager(  879): Activity pause timeout for ActivityRecord{c21667b u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6420): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6420): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6420): CordovaWebView is running on device made by: motorola
,W/art     ( 6420): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6420): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6420): Render dirty regions requested: true
,D/Atlas   ( 6420): Validating map...
,W/chromium( 6420): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6420): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6420): Enabling debug mode 0
,I/Keyboard.Facilitator( 1413): onFinishInput()
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1069
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +928ms (total +1s69ms)
,W/IInputConnectionWrapper( 6420): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6420): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 6420): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6420): Cannot call determinedVisibility() - never saw a connection for the pid: 6420
,D/JsMessageQueue( 6420): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6420): JniHelper::setJavaVM(0xb7ca3310), pthread_self() = -1207760096
D/JX-Cordova( 6420): jxcore cordova android initializing
,I/art     ( 6420): Background sticky concurrent mark sweep GC freed 29250(3MB) AllocSpace objects, 11(2MB) LOS objects, 26% free, 14MB/19MB, paused 5.212ms total 66.276ms
,W/jxcore-log( 6420): Initializing JXcore engine
W/jxcore-log( 6420): JXcore engine is ready
,W/jxcore-log( 6420): Starting JXcore engine
,W/.test.thalitest( 6420): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10449 path="socket:[9340]" dev="sockfs" ino=9340 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6420): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10449 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3086 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6420): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10449 path="socket:[8732]" dev="sockfs" ino=8732 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6420): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10449 path="socket:[27832]" dev="sockfs" ino=27832 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6420): Platform android
W/jxcore-log( 6420): 
,W/jxcore-log( 6420): Process ARCH arm
W/jxcore-log( 6420): 
,I/jxcore-log( 6420): JXcore Cordova bridge is ready!
I/jxcore-log( 6420): 
W/jxcore-log( 6420): JXcore engine is started
I/Choreographer( 6420): Skipped 177 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6420): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6420): Toggling radios to true
I/jxcore-log( 6420): 
,D/BluetoothAdapter( 6420): enable(): BT is already enabled..!
,D/WifiService(  879): New client listening to asynchronous messages
,D/WifiService(  879): setWifiEnabled: true pid=6420, uid=10449
E/WifiService(  879): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6420): Radios toggled
I/jxcore-log( 6420): 
I/jxcore-log( 6420): My device name is: motorola-XT1072
I/jxcore-log( 6420): 
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
E/WifiStateMachine(  879): WifiStateMachine: Leaving Connected state
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  879): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
D/Tethering(  879): InitialState.processMessage what=4
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/Settings(  879): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  879): ApnList is empty for checkDunConfigured()
D/Tethering(  879):  upstream interface types: 
D/Tethering(  879):  1
D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 21
D/TCMD    (  483): Listening for incoming client connection request
,V/NativeCrypto( 1734): Read error: ssl=0xb7fcd5d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xb7fcd5d8: I/O error during system call, Broken pipe
D/Tethering(  879):  5
D/Tethering(  879):  7
D/Tethering(  879):  0
D/Tethering(  879): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  879): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  879): connected time updated 120761
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  879): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager(  879): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6487 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  879): Start Disconnecting Watchdog 1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  879): ConnectModeState: Network connection lost 
E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityService(  879): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  879): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  879): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Disconnected - quitting
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  879): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/ConnectivityService(  879): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
W/ResourcesManager( 6487): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  879): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6518 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6189:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/art     (  879): Explicit concurrent mark sweep GC freed 47139(2MB) AllocSpace objects, 3(226KB) LOS objects, 33% free, 20MB/30MB, paused 1.619ms total 148.630ms
,W/libprocessgroup(  879): failed to open /acct/uid_10057/pid_6189/cgroup.procs: No such file or directory
,W/ResourcesManager( 6518): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,E/WifiStateMachine(  879): [1,452,773,932,812 ms] noteScanEnd no scan source
I/wpa_supplicant( 1408): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/WifiMonitor(  879): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1408): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3be6b4cc sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  879): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 897 seconds from now (1452773932898)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/TCMD    (  483): NL - Read 312 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 192 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1408): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  879): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  879): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  879): ApnList is empty for checkDunConfigured()
D/Tethering(  879):  upstream interface types: 
D/Tethering(  879):  0
D/Tethering(  879):  1
D/Tethering(  879):  5
D/Tethering(  879):  7
D/Tethering(  879): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1408): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  292): get_freq !!, resp=2412
I/MDMCTBK (  292): get_freq !!, Strip data
I/MDMCTBK (  292): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1199469312
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  879): Network connection established
E/WifiStateMachine(  879): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  879): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  879): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  879): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  879): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  879): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  290): Setting iface cfg
I/Babel_SMS( 6518): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6518): MmsConfig.loadMmsSettings
E/WifiStateMachine(  879): Start Dhcp Watchdog 2
I/Babel_SMS( 6518): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6518): MmsConfig.loadFromDatabase
E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  879): do suspend false
I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  879): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  879): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c773e4c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c773e4c target=com.android.internal.util.StateMachine$SmHandler }
,E/Babel_SMS( 6518): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6518): MmsConfig.loadFromResources
E/Babel_SMS( 6518): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6518): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6518): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6518): startup - clean
,I/Babel   ( 6518): deleted: false for 0
,D/Uploader( 1734): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/DHCPCD  ( 6557): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6557): version 5.5.6 starting
,E/DHCPCD  ( 6557): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6557): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6557): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/VideoCapabilities( 6518): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6518): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6518): Unsupported mime video/mpeg2
,D/DHCPCD  ( 6557): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6557): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6557): wlan0: sending REQUEST (xid 0x20f8a342), next in 4.32 seconds
,I/VideoCapabilities( 6518): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6518): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6518): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6518): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6518): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  879): Killing 6227:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/DHCPCD  ( 6557): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6557): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6557): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6557): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6557): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6557): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 20
D/TCMD    (  483): Listening for incoming client connection request
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/DHCPCD  ( 6557): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_6227/cgroup.procs: No such file or directory
I/vclib   ( 6518): onServiceConnected
W/Babel   ( 6518): Attempted to change video mute state without an active call.
,D/Uploader( 1734): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  879): WifiStateMachine DHCP successful
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  879): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  879): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  879): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  879): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  879): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  879): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  879): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  879): Setting Dns servers for network 101 to [/192.168.1.1]
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  879): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  879): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Nat464Xlat(  879): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  879): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  879): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 12:18:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452773934026], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452773934003]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Validated
,D/ConnectivityService(  879): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524290
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1288): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1532): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1532): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  879): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  879): MasterInitialState.processMessage what=3
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6607 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  879): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1469): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2643): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2643): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2643): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2643): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2643): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2643): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2643): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2643): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2643): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2643): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2643): [debug] > CusSM.onRadioDown
,I/MusicStore( 6607): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6607): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6607): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6607): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6607): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  879): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524295
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,V/JNIHelp ( 6607): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6607): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6607): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5586e34: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6607): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6607): GMSCore installation verified
,I/ConfigStore( 6607): Config Database version: 1
,I/MediaRouter( 6607): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6607): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6607): type=WIFI subType= reason=null isConnected=true
,E/global frequency( 2643): no tags to log
,D/Checkin ( 2643): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2643): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/NetworkMonitor( 6607): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6650 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6607): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     ( 2643): Explicit concurrent mark sweep GC freed 30326(1775KB) AllocSpace objects, 5(103KB) LOS objects, 39% free, 11MB/19MB, paused 2.086ms total 109.220ms
,I/GoogleURLConnFactory( 6607): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  879): Killing 6036:android.process.acore/u0a7 (adj 15): empty #7
,D/BSUtils ( 2643): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2643): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6036/cgroup.procs: No such file or directory
V/AlarmManager(  879): send {21b866d7, *walarm*:com.google.android.intent.action.SEND_IDLE}
,D/BSUtils ( 2643): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  879): Explicit concurrent mark sweep GC freed 37008(1822KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.637ms total 121.946ms
,V/Mms     ( 6650): mnc/mcc: 
V/Mms     ( 6650): tag: int value: recipientLimit - 20
V/Mms     ( 6650): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6650): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6650): tag: int value: maxSubjectLength - 80
V/Mms     ( 6650): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6650): tag: bool value: enableGroupMms - false
V/Mms     ( 6650):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 55864(3MB) AllocSpace objects, 36(1227KB) LOS objects, 39% free, 7MB/12MB, paused 810us total 48.728ms
,W/ResourcesManager( 6650): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BSUtils ( 2643): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6690 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.056ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 18.941ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.557ms
,I/BSUtils ( 2643): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2643): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  879): Killing 6113:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6690): Register our PhoneStateListener
,D/BSUtils ( 2643): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2643): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_6113/cgroup.procs: No such file or directory
,D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2643): now: 196652 ,futureTime: 9223372036854775807
D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2643): now: 196653 ,futureTime: 9223372036854775807
D/PollingManager( 2643): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2643): now: 196653 ,futureTime: 9223372036854775807
,D/Tethering(  879): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1469): now: 196658 ,futureTime: 86475548
D/Central_PollingManager( 1469): Polling alarm set to expire at: 86475548 Current Time: 196658
I/BSUtils ( 2643): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/OtaApp  ( 2643): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6607): type=WIFI subType= reason=null isConnected=true
,I/global frequency( 2643): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/OtaApp  ( 2643): [debug] > PollingManagerService, now: 196663 ,futureTime: 20718831
D/OtaApp  ( 2643): [debug] > Polling alarm set to expire at: 20718831 Current Time: 196664
,D/Checkin ( 2643): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2643): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2643): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2643): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/MobileConnectivityChangeReceiver( 6690): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6690): onReceive CONNECTIVITY_CHANGE networkType=1
,D/Checkin ( 2643): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,D/MMApiProvisionService( 2643): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2643): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2643): createDeviceIdOrLogin update_device
,D/Checkin ( 2643): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2643): Not proxy app, so login/provision not allowed
,I/ActivityManager(  879): Killing 6518:com.google.android.talk/u0a70 (adj 15): empty #7
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 4540(195KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 527us total 30.185ms
,D/MMApiProvisionService( 2643): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2643): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2643): createDeviceIdOrLogin update_device
,D/Checkin ( 2643): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2643): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2643): set mOutstandingReq to true.
,I/ Nonce  ( 2643):  Nonce getNonce 
I/ Nonce  ( 2643):  Nonce Request 
I/ Nonce  ( 2643):  Nonce execute Request 
,D/MMApiWebService( 2643): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2643): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2643): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2643): createDeviceIdOrLogin update_device
,D/Checkin ( 2643): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2643): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2643): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2643): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2643): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2643): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2643): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2643): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2643): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2643): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2643): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/art     ( 2643): Explicit concurrent mark sweep GC freed 10538(582KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/19MB, paused 1.041ms total 64.091ms
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_6518/cgroup.procs: No such file or directory
,D/OtaApp  ( 2643): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2643): generating token using payload instead of using session token
,D/ Nonce  ( 2643):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/CheckinService( 6297): Checkin interval check for package: unspecified last checkin: 1452773856250 min interval config: 0 actual interval: 80996
,I/MMApiWSBase( 2643): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2643): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinService( 6297): Disabling old GoogleServicesFramework version
,I/CheckinService( 6297): Checking schedule, now: 1452773937273 next: 1452773886226
I/CheckinService( 6297): active receiver: enabled
,I/iu.SyncManager( 6297): SYNC; picasa accounts
,I/CheckinService( 6297): Preparing to send checkin request
,D/NetworkLogImpl( 6297): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6297): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6297): Accumulating logs since 1452773852873
,I/iu.UploadsManager( 6297): num queued entries: 0
,I/iu.UploadsManager( 6297): num updated entries: 0
,I/iu.SyncManager( 6297): NEXT; no task
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6719 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6297): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 6297): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  879): Explicit concurrent mark sweep GC freed 9246(434KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.614ms total 117.811ms
D/WifiService(  879): New client listening to asynchronous messages
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6741 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6758 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6741): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6758): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6758): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6758): VM with version 2.1.0 has multidex support
I/MultiDex( 6758): install
I/MultiDex( 6758): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6758): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ Nonce  ( 2643):  Nonce Reponse 
D/        ( 2643): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"61650257-6f49-4b11-be37-1b454955eb9f"}
D/MMApiWSBase( 2643): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2643):  Nonce Handle Reponse 
D/MMApiProvisionService( 2643): mOutstandingReq set to false
,W/ActivityThread( 6758): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6758): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@123970c5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6758): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 6741): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6741): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6741): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6741): MmsConfig.loadFromDatabase
,I/art     ( 6758): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6758): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Babel_SMS( 6741): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6741): MmsConfig.loadFromResources
,E/Babel_SMS( 6741): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6741): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6741): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MMApiProvisionService( 2643):  pTime 1452672215335 sExp 172742 cTime 1452773938403 tTime 1452844957335
D/MMApiProvisionService( 2643):  No login Required 
,I/Babel_Crash( 6741): startup - clean
,D/NativeLibraryUtils( 6758): Install completed successfully. count=14 extracted=0
I/art     ( 6266): Explicit concurrent mark sweep GC freed 1991(87KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 379us total 26.478ms
D/WVCdm   (  294): Instantiating CDM.
I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
I/Babel   ( 6741): deleted: false for 0
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f5f000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f5f000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb124f960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb73350a8, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb73b9548, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7404d40, idLength=0xbeef52b0
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=4231018728
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb73aab38
D/DrmWidevineDash(  294): message_length=1591, signature=0xb72e68f8, signature_length=3203355284
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6798 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/DataUsage( 2643): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2643): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/VideoCapabilities( 6741): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6741): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 6741): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6741): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6741): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6741): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6741): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6741): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6741): onServiceConnected
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/Babel   ( 6741): Attempted to change video mute state without an active call.
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f5f000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f5f000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb124f960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb72e6910, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb73b9548, wrapped_rsa_key_length=1280
I/Babel   ( 6741): connection state changed from UNKNOWN to CONNECTED
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7404d80, idLength=0xb5539730
I/ActivityManager(  879): Killing 6487:com.motorola.context/u0a8 (adj 15): empty #7
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
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3916349849
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb73aab38
D/DrmWidevineDash(  294): message_length=1626, signature=0xb72e6be0, signature_length=3042154260
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
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
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_6487/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6798): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6798): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6798): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6798):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6798):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6798): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6798): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6798): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6798): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6798): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6835): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6835): dex2oat took 168.842ms (threads: 4)
,I/Adreno-EGL( 6758): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6758): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6758): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6758): Local Branch: 
I/Adreno-EGL( 6758): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6758): Local Patches: NONE
I/Adreno-EGL( 6758): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 6798): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Adreno-EGL( 6758): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6758): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6758): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6758): Local Branch: 
I/Adreno-EGL( 6758): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6758): Local Patches: NONE
I/Adreno-EGL( 6758): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/LibraryLoader( 6798): Time to load native libraries: 1 ms (timestamps 9506-9507)
,I/LibraryLoader( 6798): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6798): Binding Chromium to main looper Looper (main, tid 1) {25311535}
,I/LibraryLoader( 6798): Expected native library version number "",actual native library version number ""
I/chromium( 6798): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6798): Initializing chromium process, singleProcess=true
,W/art     ( 6798): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6798): ApplicationContext is null in ApplicationStatus
,W/chromium( 6798): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6798): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6798): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6798): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6798): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6798): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6798): Local Branch: 
I/Adreno-EGL( 6798): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6798): Local Patches: NONE
I/Adreno-EGL( 6798): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 6798): Starting up...
,W/AudioManagerAndroid( 6798): Requires BLUETOOTH permission
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6877 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 6607:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_6607/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6758): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6758): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6758): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6758): Local Branch: 
I/Adreno-EGL( 6758): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6758): Local Patches: NONE
I/Adreno-EGL( 6758): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6758): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6758): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6758): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6758): Local Branch: 
I/Adreno-EGL( 6758): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6758): Local Patches: NONE
I/Adreno-EGL( 6758): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6297): Classify the device as Phone.
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6903 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 6650:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_6650/cgroup.procs: No such file or directory
,W/ResourcesManager( 6903): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6925 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ContactLocale( 6925): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6959 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 6719:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/CheckinTask( 6297): Sending checkin request (9524 bytes)
,I/ActivityManager(  879): Killing 6690:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_6719/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_6690/cgroup.procs: No such file or directory
,I/MusicStore( 6959): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6959): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6959): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6959): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6959): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6959): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6959): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6959): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5586e34: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6959): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6959): GMSCore installation verified
,I/ConfigStore( 6959): Config Database version: 1
,I/CheckinRequestBuilder( 6297): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6297): Failed to find provider info for com.google.android.wearable.settings
,I/MediaRouter( 6959): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6959): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6959): type=WIFI subType= reason=null isConnected=true
,I/art     (  879): Explicit concurrent mark sweep GC freed 10252(508KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.998ms total 112.186ms
,I/NetworkMonitor( 6959): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7001 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6959): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6959): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  879): Killing 6741:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7001): mnc/mcc: 
V/Mms     ( 7001): tag: int value: recipientLimit - 20
I/CheckinRequestBuilder( 6297): Classify the device as Phone.
,V/Mms     ( 7001): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7001): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7001): tag: int value: maxSubjectLength - 80
V/Mms     ( 7001): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7001): tag: bool value: enableGroupMms - false
,V/Mms     ( 7001):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_6741/cgroup.procs: No such file or directory
,I/CheckinTask( 6297): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6297): Checking schedule, now: 1452773942538 next: 1453375079530
I/CheckinService( 6297): active receiver: disabled
,D/CheckinService( 6297): Recording last checkin time for package unspecified as 1452773942547
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309922, SEQNUM=4461, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-254, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ActivityManager(  879): Killing 6877:com.android.chrome/u0a52 (adj 13): empty #7
W/ResourcesManager( 7001): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Killing 6798:com.google.android.apps.magazines/u0a81 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10081/pid_6798/cgroup.procs: No such file or directory
,W/BroadcastQueue(  879): Failure sending broadcast Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/BroadcastQueue(  879): android.os.RemoteException: app.thread must not be null
W/BroadcastQueue(  879): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:453)
W/BroadcastQueue(  879): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:539)
W/BroadcastQueue(  879): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:587)
W/BroadcastQueue(  879): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:154)
W/BroadcastQueue(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  879): 	at android.os.Looper.loop(Looper.java:135)
W/BroadcastQueue(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue(  879): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,D/HeadsetStateMachine( 2499): Disconnected process message: 10, size: 0
W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_6877/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7040 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6925:android.process.acore/u0a7 (adj 13): empty #7
,D/PhoneMonitor( 7040): Register our PhoneStateListener
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6925/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7040): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7040): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  879): Killing 6903:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_6903/cgroup.procs: No such file or directory
,I/CheckinService( 6297): Checkin interval check for package: unspecified last checkin: 1452773942547 min interval config: 0 actual interval: 1007
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7059 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 317us total 22.627ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 18.832ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.404ms
,I/CheckinService( 6297): Checking schedule, now: 1452773943658 next: 1452773972530
I/CheckinService( 6297): active receiver: disabled
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7084 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6959:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_6959/cgroup.procs: No such file or directory
,W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7084): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7084): MmsConfig.loadMmsSettings
I/Babel_SMS( 7084): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7084): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7084): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7084): MmsConfig.loadFromResources
,E/Babel_SMS( 7084): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7084): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7084): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7084): startup - clean
,I/Babel   ( 7084): deleted: false for 0
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7127 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7084): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7084): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7084): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7084): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7084): onServiceConnected
W/Babel   ( 7084): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7127): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7127): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7127):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7127):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7127): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7084): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  879): Killing 7001:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7127): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7127): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 6420): Test app app.js loaded
I/jxcore-log( 6420): 
,I/Choreographer( 6420): Skipped 769 frames!  The application may be doing too much work on its main thread.
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_7001/cgroup.procs: No such file or directory
,I/chromium( 6420): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/GAv4    ( 7127): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7127): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7127): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7127): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7127): Time to load native libraries: 1 ms (timestamps 4832-4833)
,I/LibraryLoader( 7127): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7127): Binding Chromium to main looper Looper (main, tid 1) {25311535}
,I/LibraryLoader( 7127): Expected native library version number "",actual native library version number ""
I/chromium( 7127): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7127): Initializing chromium process, singleProcess=true
,W/art     ( 7127): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7127): ApplicationContext is null in ApplicationStatus
,W/chromium( 7127): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7127): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7127): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7127): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7127): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7127): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7127): Local Branch: 
I/Adreno-EGL( 7127): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7127): Local Patches: NONE
I/Adreno-EGL( 7127): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7127): Requires BLUETOOTH permission
,I/NSApplication( 7127): Starting up...
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7191 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7040:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7040/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7210 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7059:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7059/cgroup.procs: No such file or directory
,W/ResourcesManager( 7210): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7233 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7127:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 7233): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Killing 7084:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2643): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  879): failed to open /acct/uid_10081/pid_7127/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7084/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2643): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2643): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2643): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2643): onServiceConnected()
D/GetNotificationsWS( 2643): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2643): unbindWebServices(): un-registering our AIDL callback...
,V/AlarmManager(  879): done {21b866d7, *walarm*:com.google.android.intent.action.SEND_IDLE} [9844ms]
,I/PushService( 2643): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7263 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7263): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7263): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7263): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7263): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7263): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7263): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5586e34: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7263): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7263): GMSCore installation verified
,I/ConfigStore( 7263): Config Database version: 1
,I/MediaRouter( 7263): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7263): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7263): type=WIFI subType= reason=null isConnected=true
,I/art     (  879): Explicit concurrent mark sweep GC freed 12301(650KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.519ms total 113.146ms
,I/NetworkMonitor( 7263): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7295 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7263): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7263): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  879): Killing 6758:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7295): mnc/mcc: 
V/Mms     ( 7295): tag: int value: recipientLimit - 20
,V/Mms     ( 7295): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7295): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7295): tag: int value: maxSubjectLength - 80
V/Mms     ( 7295): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7295): tag: bool value: enableGroupMms - false
V/Mms     ( 7295):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_6758/cgroup.procs: No such file or directory
,W/ResourcesManager( 7295): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7326 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7191:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7326): Register our PhoneStateListener
,W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_7191/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7326): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7326): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  879): Killing 7210:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7210/cgroup.procs: No such file or directory
,I/CheckinService( 6297): Checkin interval check for package: unspecified last checkin: 1452773942547 min interval config: 0 actual interval: 4571
,I/CheckinService( 6297): Checking schedule, now: 1452773947126 next: 1452773972530
I/CheckinService( 6297): active receiver: disabled
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7345 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  879): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  879): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7373 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7233:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7233/cgroup.procs: No such file or directory
,V/BackupManagerService(  879): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@311d6805
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1567): Deferring update until onResume
,I/Babel_SMS( 7373): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7373): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7373): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7373): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7373): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7373): MmsConfig.loadFromResources
,E/Babel_SMS( 7373): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7373): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7373): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7373): startup - clean
,I/Babel   ( 7373): deleted: false for 0
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7406 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 20.023ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.077ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.507ms
,W/VideoCapabilities( 7373): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7373): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7373): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7373): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7373): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7373): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7373): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7373): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7373): onServiceConnected
W/Babel   ( 7373): Attempted to change video mute state without an active call.
,I/GAv4    ( 7406): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7406):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7406):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7406): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7406): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7406): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7406): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7406): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7406): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7373): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  879): Killing 7263:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7406): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_7263/cgroup.procs: No such file or directory
,I/WebViewFactory( 7406): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7406): Time to load native libraries: 2 ms (timestamps 8181-8183)
I/LibraryLoader( 7406): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7406): Binding Chromium to main looper Looper (main, tid 1) {25311535}
,I/LibraryLoader( 7406): Expected native library version number "",actual native library version number ""
I/chromium( 7406): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7406): Initializing chromium process, singleProcess=true
,W/art     ( 7406): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7406): ApplicationContext is null in ApplicationStatus
,W/chromium( 7406): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7406): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7406): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7406): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7406): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7406): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7406): Local Branch: 
I/Adreno-EGL( 7406): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7406): Local Patches: NONE
I/Adreno-EGL( 7406): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7406): Starting up...
,W/AudioManagerAndroid( 7406): Requires BLUETOOTH permission
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7477 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 7295:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_7295/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7496 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 7326:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7326/cgroup.procs: No such file or directory
,W/ResourcesManager( 7496): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7516 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7373:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  879): Killing 7345:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 7516): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7373/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2643): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7345/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2643): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2643): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2643): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2643): onServiceConnected()
D/GetNotificationsWS( 2643): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 2643): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2643): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2643): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2643): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  879): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2643): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7546 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2643): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2643): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2643): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2643): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2643): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2643): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2643): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2643): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2643): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2643): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2643): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2643): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6420): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1413): onFinishInput()
,I/LaunchCheckinHandler(  879): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,169
,I/art     (  879): Explicit concurrent mark sweep GC freed 18242(912KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.624ms total 118.399ms
,D/WearableService( 1734): callingUid 10016, callindPid: 1734
,E/MDM     ( 1734): [174] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6297): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7573 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7573): Register our PhoneStateListener
,V/SetupWizard( 7573): Connected to Gservices successfully
,I/ActivityManager(  879): Killing 7406:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10081/pid_7406/cgroup.procs: No such file or directory
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7597 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7621 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7636 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7477:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  879): Killing 7496:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_7477/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7496/cgroup.procs: No such file or directory
,W/ResourcesManager( 7636): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7636): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7636): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7636): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7636): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7636): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7636): MmsConfig.loadFromResources
E/Babel_SMS( 7636): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7636): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7636): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7636): startup - clean
,I/Babel   ( 7636): deleted: false for 0
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7671 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7636): Unrecognized profile 2130706433 for video/avc
,W/asset   ( 7671): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7671): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7671): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7671): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/AudioCapabilities( 7636): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7636): Unsupported mime video/mpeg2
,D/PackageBroadcastService( 6297): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 7597): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@19b5fd62 new=com.google.android.velvet.VelvetApplication@19b5fd62
,I/PackageBroadcastService( 6297): Null package name or gms related package.  Ignoreing.
I/VideoCapabilities( 7636): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7636): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7636): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7636): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7636): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7695 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 6297): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 7597): UpdateCorporaTask done [took 192 ms] updated apps [took 192 ms] 
,I/ActivityManager(  879): Killing 7546:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7546/cgroup.procs: No such file or directory
,I/vclib   ( 7636): onServiceConnected
W/Babel   ( 7636): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7636): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7636): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7636): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7636): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7636): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7737 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 19.991ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 729us total 20.500ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.975ms
I/ActivityManager(  879): Killing 7573:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7573/cgroup.procs: No such file or directory
,I/art     ( 6266): Explicit concurrent mark sweep GC freed 1888(72KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 407us total 32.211ms
,D/Finsky  ( 7737): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7737): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7737): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7737): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7737): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7737): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7737): Skipping gmscore version check
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7784 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7621:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_7621/cgroup.procs: No such file or directory
,D/Finsky  ( 7737): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/TaskPersister(  879): removeObsoleteFile: deleting file=5_task.xml
,D/Finsky  ( 7737): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6297): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6297): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6297): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  879): Killing 7671:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_7671/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7597:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_7597/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7516:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7516/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 6297): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309798, SEQNUM=4496, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-281, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2499): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {36f6c9e5, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {4846ff5, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  879): send {c934f8f, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  879): done {4846ff5, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [17ms]
,V/AlarmManager(  879): done {c934f8f, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [35ms]
,I/CheckinService( 6297): Checkin interval check for package: unspecified last checkin: 1452773942547 min interval config: 0 actual interval: 44595
,V/AlarmManager(  879): done {36f6c9e5, *alarm*:android.intent.action.TIME_TICK} [55ms]
,I/CheckinService( 6297): Checking schedule, now: 1452773987164 next: 1452773972530
I/CheckinService( 6297): active receiver: enabled
,I/CheckinService( 6297): Preparing to send checkin request
I/EventLogService( 6297): Accumulating logs since 1452773937524
,I/CheckinRequestBuilder( 6297): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6297): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  879): Explicit concurrent mark sweep GC freed 15638(782KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.523ms total 113.417ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7860 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7860): VM with version 2.1.0 has multidex support
I/MultiDex( 7860): install
I/MultiDex( 7860): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7860): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7860): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7860): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@123970c5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7860): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1734): callingUid 10016, callindPid: 1734
,E/MDM     ( 1734): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6297): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,I/art     ( 7860): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7860): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7860): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
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
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f5f000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f5f000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb5439960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb72d3ce0, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb73b9548, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7404d60, idLength=0xbeef52b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3875453635
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb73aab38
D/DrmWidevineDash(  294): message_length=1591, signature=0xb72be830, signature_length=3203355284
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f5f000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f5f000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb124f960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb72beb20, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb73b9548, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7404d80, idLength=0xbeef52b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=2750028532
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb73aab38
D/DrmWidevineDash(  294): message_length=1626, signature=0xb72e6970, signature_length=3203355284
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7906): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7906): dex2oat took 58.690ms (threads: 4)
,I/Adreno-EGL( 7860): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7860): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7860): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7860): Local Branch: 
I/Adreno-EGL( 7860): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7860): Local Patches: NONE
I/Adreno-EGL( 7860): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7860): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7860): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7860): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7860): Local Branch: 
I/Adreno-EGL( 7860): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7860): Local Patches: NONE
I/Adreno-EGL( 7860): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7860): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7860): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7860): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7860): Local Branch: 
I/Adreno-EGL( 7860): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7860): Local Patches: NONE
I/Adreno-EGL( 7860): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7860): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7860): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7860): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7860): Local Branch: 
I/Adreno-EGL( 7860): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7860): Local Patches: NONE
I/Adreno-EGL( 7860): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6297): Classify the device as Phone.
,I/CheckinTask( 6297): Sending checkin request (9512 bytes)
,I/CheckinRequestBuilder( 6297): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6297): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6297): Classify the device as Phone.
,I/CheckinTask( 6297): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6297): Checking schedule, now: 1452773990911 next: 1453375127906
I/CheckinService( 6297): active receiver: disabled
,D/CheckinService( 6297): Recording last checkin time for package unspecified as 1452773990921
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7925 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7925): Register our PhoneStateListener
,V/SetupWizard( 7925): Connected to Gservices successfully
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  879): Killing 7737:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  879): Killing 7695:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_7737/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7695/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7948 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  879): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  879): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@322e018b
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 106676(5MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 15MB/25MB, paused 1.195ms total 111.910ms
,E/DataBuffer( 1734): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@cb30f7d)
,E/DataBuffer( 1734): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ea3de72)
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7986 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8008 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7784:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7784/cgroup.procs: No such file or directory
,W/ResourcesManager( 7636): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7636): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8008): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8031 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 7925:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7925/cgroup.procs: No such file or directory
,W/asset   ( 8031): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8031): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8031): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8031): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6297): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6297): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 6297): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@19b5fd62 new=com.google.android.velvet.VelvetApplication@19b5fd62
I/UpdateIcingCorporaServi( 7948): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8058 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 7948): UpdateCorporaTask done [took 129 ms] updated apps [took 129 ms] 
,I/art     (  879): Explicit concurrent mark sweep GC freed 17351(900KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.103ms total 126.776ms
,W/ResourcesManager( 8058): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8088 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7860:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_7860/cgroup.procs: No such file or directory
,D/Finsky  ( 8088): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8088): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8088): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8088): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8088): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8088): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8088): Skipping gmscore version check
,D/Finsky  ( 8088): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8088): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  879): Killing 7986:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_7986/cgroup.procs: No such file or directory
,I/Icing   ( 6297): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6297): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  879): Killing 8031:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_8031/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7636:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7636/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1734): onCreate
,I/ConfigService( 1734): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309379, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-333, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2499): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6420): --= Surplus to requirements =--
I/jxcore-log( 6420): 
I/jxcore-log( 6420): ****TEST TOOK:  ms ****
I/jxcore-log( 6420): 
I/jxcore-log( 6420): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6420): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/AndroidRuntime( 8155): 
D/AndroidRuntime( 8155): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8155): CheckJNI is OFF
,D/AndroidRuntime( 8155): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  879): Force stopping com.test.thalitest appid=10449 user=-1: uninstall pkg
,I/ActivityManager(  879): Killing 6420:com.test.thalitest/u0a449 (adj 9): stop com.test.thalitest
,W/PackageSettings(  879): Skipping PackageSetting{1d546ac9 com.example.hello/10440} due to missing metadata
I/WindowState(  879): WIN DEATH: Window{e94355e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  879): Client connection lost with reason: 4
,I/ActivityManager(  879):   Force finishing activity ActivityRecord{c21667b u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  879): Spurious death for ProcessRecord{3d1c53a4 6420:com.test.thalitest/u0a449}, curProc for 6420: null
,I/ActivityManager(  879): Force stopping com.test.thalitest appid=10449 user=0: pkg removed
,I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
,D/VoicemailCleanupService( 8008): Cleaning up data for package: com.test.thalitest
I/art     ( 3039): Explicit concurrent mark sweep GC freed 9616(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/12MB, paused 728us total 76.720ms
,I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8185 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 5061(311KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 472us total 121.380ms
,I/Decoder ( 1413): createOrResetDecoder
I/art     (  879): Explicit concurrent mark sweep GC freed 12904(892KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.566ms total 160.410ms
,I/art     (  879): WaitForGcToComplete blocked for 57.886ms for cause Explicit
,I/ConfigService( 1734): onCreate
,W/asset   ( 8185): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8185): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8185): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8185): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8209 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  879): removeObsoleteFile: deleting file=6_task.xml
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 20.717ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 18.968ms
,I/ActivityManager(  879): Killing 7948:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.076ms
,I/Launcher( 1567): Deferring update until onResume
,I/art     (  879): Explicit concurrent mark sweep GC freed 6017(307KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.066ms total 216.629ms
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_7948/cgroup.procs: No such file or directory
,D/AndroidRuntime( 8155): Shutting down VM
,W/ContextImpl( 8209): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6297): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 6297): Reading stored module config
,D/AccountUtils( 6297): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6297): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6297): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 6297): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6297): App measurement is starting up, version: 8489
,I/GMPM-SVC( 6297): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1734): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1734): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 6297): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6297): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6297): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6297): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8240 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 6297): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6297): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6297): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6297): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6297): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6297): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6297): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6297): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6297): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@19b5fd62 new=com.google.android.velvet.VelvetApplication@19b5fd62
,D/ChimeraCfgMgr( 6297): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6297): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8262 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Icing   ( 6297): doRemovePackageData com.test.thalitest
,W/BaseAppContext( 6297): Using Auth Proxy for data requests.
,E/BaseAppContext( 6297): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/SQLiteLog( 6297): (778) statement aborts at 16: [INSERT OR REPLACE  INTO properties(name,value) VALUES (?,?)] 
,E/SQLiteDatabase( 6297): Error inserting name=gcoreVersion value=8489236
E/SQLiteDatabase( 6297): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
E/SQLiteDatabase( 6297): 	at android.database.sqlite.SQLiteDatabase.replace(SQLiteDatabase.java:1387)
E/SQLiteDatabase( 6297): 	at com.google.android.gms.people.c.f.a(SourceFile:2539)
E/SQLiteDatabase( 6297): 	at com.google.android.gms.people.c.f.b(SourceFile:2529)
E/SQLiteDatabase( 6297): 	at com.google.android.gms.people.c.f.b(SourceFile:788)
E/SQLiteDatabase( 6297): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 6297): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 6297): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 6297): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 6297): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 6297): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6297): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6297): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8300 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
W/BaseAppContext( 6297): Using Auth Proxy for data requests.
W/BaseAppContext( 6297): Using Auth Proxy for data requests.
E/SQLiteLog( 6297): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/BaseAppContext( 6297): Using Auth Proxy for data requests.
--------- beginning of crash
E/AndroidRuntime( 6297): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6297): Process: com.google.android.gms, PID: 6297
E/AndroidRuntime( 6297): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6297): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6297): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6297): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6297): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6297): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6297): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6297): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6297): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6297): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6297): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6297): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6297): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6297): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6297): Sending signal. PID: 6297 SIG: 9
,I/UpdateIcingCorporaServi( 8240): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/WifiService(  879): Client connection lost with reason: 4
,E/SQLiteLog( 8240): (778) statement aborts at 16: [DELETE FROM applications WHERE uri=?] 
,I/ActivityManager(  879): Process com.google.android.gms (pid 6297) has died
,W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
,W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10999ms
,W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
,W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
E/SQLiteLog( 8240): (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
