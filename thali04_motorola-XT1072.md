#### Test 5065027881383b1_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,D/AndroidRuntime( 6742): 
D/AndroidRuntime( 6742): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6742): CheckJNI is OFF
D/AndroidRuntime( 6742): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  887): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6761 uid=10377 gids={50377, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6742): Shutting down VM
V/ActivityManager(  887): Display changed displayId=0
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6761): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6761): Time to load native libraries: 2 ms (timestamps 8279-8281)
I/LibraryLoader( 6761): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6761): Binding Chromium to main looper Looper (main, tid 1) {274d369b}
,I/LibraryLoader( 6761): Expected native library version number "",actual native library version number ""
I/chromium( 6761): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6761): Initializing chromium process, singleProcess=true
W/art     ( 6761): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6761): ApplicationContext is null in ApplicationStatus
,W/chromium( 6761): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6761): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6761): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6761): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6761): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6761): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6761): Local Branch: 
I/Adreno-EGL( 6761): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6761): Local Patches: NONE
I/Adreno-EGL( 6761): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cbde966:true
,W/ActivityManager(  887): Activity pause timeout for ActivityRecord{184c4053 u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6761): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6761): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6761): CordovaWebView is running on device made by: motorola
,W/art     ( 6761): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6761): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6761): Render dirty regions requested: true
,D/Atlas   ( 6761): Validating map...
,W/chromium( 6761): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6761): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6761): Enabling debug mode 0
,I/Keyboard.Facilitator( 1421): onFinishInput()
,I/LaunchCheckinHandler(  887): Displayed com.test.thalitest/.MainActivity,cp,ca,931
I/ActivityManager(  887): Displayed com.test.thalitest/.MainActivity: +856ms (total +931ms)
,W/IInputConnectionWrapper( 6761): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6761): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6761): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6761): Cannot call determinedVisibility() - never saw a connection for the pid: 6761
,D/JsMessageQueue( 6761): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6761): JniHelper::setJavaVM(0xb813c310), pthread_self() = -1202922648
,D/JX-Cordova( 6761): jxcore cordova android initializing
,W/jxcore-log( 6761): Initializing JXcore engine
W/jxcore-log( 6761): JXcore engine is ready
,W/jxcore-log( 6761): Starting JXcore engine
,W/.test.thalitest( 6761): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10377 path="socket:[7348]" dev="sockfs" ino=7348 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6761): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10377 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6761): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10377 path="socket:[7492]" dev="sockfs" ino=7492 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6761): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10377 path="socket:[27590]" dev="sockfs" ino=27590 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6761): Platform android
W/jxcore-log( 6761): 
W/jxcore-log( 6761): Process ARCH arm
W/jxcore-log( 6761): 
,I/jxcore-log( 6761): JXcore Cordova bridge is ready!
I/jxcore-log( 6761): 
W/jxcore-log( 6761): JXcore engine is started
I/Choreographer( 6761): Skipped 172 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6761): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6761): Toggling radios to true
I/jxcore-log( 6761): 
,D/BluetoothAdapter( 6761): enable(): BT is already enabled..!
,D/WifiService(  887): New client listening to asynchronous messages
,D/WifiService(  887): setWifiEnabled: true pid=6761, uid=10377
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6761): Radios toggled
I/jxcore-log( 6761): 
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6761): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6761): 
I/jxcore-log( 6761): Perf Test app loaded loaded
I/jxcore-log( 6761): 
,I/jxcore-log( 6761): check test folder
I/jxcore-log( 6761): 
,I/jxcore-log( 6761): found test : ./testFindPeers.js
I/jxcore-log( 6761): 
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  296): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  296):  STA Disconnected !!
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): get_property_value, Enter
I/MDMCTBK (  296): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  296): get_property_value, Exit
I/MDMCTBK (  296): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  296): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  296): set_property_value, Enter
I/MDMCTBK (  296): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  296): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  296): set_property_value, Exit
I/MDMCTBK (  296): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  296): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  296): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  296): set_property_value, Enter
I/MDMCTBK (  296): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
I/MDMCTBK (  296): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  296): set_property_value, Exit
E/MDMCTBK (  296): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  296): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  296): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  887): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  887): InitialState.processMessage what=4
,I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  296): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887):  0
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 6761): found test : ./testSendData.js
I/jxcore-log( 6761): 
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  293): Clearing all IP addresses on wlan0
,D/TCMD    (  487): NL - Read 60 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 21
D/TCMD    (  487): Listening for incoming client connection request
,V/NativeCrypto( 1751): Read error: ssl=0xb8464d10: I/O error during system call, Connection timed out
,V/NativeCrypto( 1751): SSL shutdown failed: ssl=0xb8464d10: I/O error during system call, Broken pipe
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=-9ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-9ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  887): connected time updated 125220
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  887): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6829 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=null
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524292
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
E/ConnectivityService(  887): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  887): Start Disconnecting Watchdog 1
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  296): Event received = CTRL-EVENT-STATE-CHANGE 
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): ConnectModeState: Network connection lost 
E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  293): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
W/ResourcesManager( 6829): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Choreographer( 6761): Skipped 121 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6761): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6853 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6572:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_6572/cgroup.procs: No such file or directory
,W/ResourcesManager( 6853): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6853): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6853): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6853): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6853): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6853): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6853): MmsConfig.loadFromResources
,E/Babel_SMS( 6853): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6853): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  296): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1408): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1408): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  296): Event received = Trying to associate with
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  296): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  887): [1,449,753,001,695 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3159281f sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/art     ( 6853): Suspending all threads took: 8.643ms
,W/Settings( 6853): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6853): startup - clean
,I/Babel   ( 6853): deleted: false for 0
,D/TCMD    (  487): NL - Read 312 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 192 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
I/wpa_supplicant( 1408): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  487): NL - Read 80 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 80 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  296): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  296): Event received = Associated with c0:ff:d4
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  296): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  296): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1408): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  296): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1408): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  296): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  296):  STA Connected !!
,D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
E/MDMCTBK (  296): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  296): get_freq !!, resp=2412
I/MDMCTBK (  296): get_freq !!, Strip data
I/MDMCTBK (  296): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): get_property_value, Enter
I/MDMCTBK (  296): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  296): get_property_value, Exit
I/MDMCTBK (  296): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  296): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  296): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  296): set_property_value, Enter
I/MDMCTBK (  296): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  296): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  296): set_property_value, Exit
I/MDMCTBK (  296): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  296): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  296): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): get_property_value, Enter
I/MDMCTBK (  296): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  296): get_property_value, Exit
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/MDMCTBK (  296): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1198207568
I/MDMCTBK (  296): return from set_get_from_wpa_supplicant
,I/MDMCTBK (  296): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  296): set_property_value, Enter
D/MDMCTBK (  296): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  296): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/MDMCTBK (  296): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  296): set_property_value, Exit
E/MDMCTBK (  296): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  296): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  296): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  296): , reply_len: 3, ret: 0
E/MDMCTBK (  296): MdmCutbackHndler, resp=OK
E/MDMCTBK (  296): 
D/MDMCTBK (  296): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  887): Network connection established
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  293): Setting iface cfg
,E/WifiStateMachine(  887): Start Dhcp Watchdog 2
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend false
,E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1408): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2378c4b target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2378c4b target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6853): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6853): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6853): Unsupported mime video/mpeg2
,E/global frequency( 2671): no tags to log
,D/Checkin ( 2671): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/VideoCapabilities( 6853): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6853): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6853): Unrecognized profile 2130706433 for video/avc
,V/AlarmManager(  887): send {d68e8a7, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {10c026f, *walarm*:com.google.android.intent.action.SEND_IDLE}
W/VideoCapabilities( 6853): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6853): Unrecognized profile 2130706433 for video/avc
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,E/DHCPCD  ( 6893): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6893): version 5.5.6 starting
E/DHCPCD  ( 6893): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6893): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6893): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/art     (  887): Explicit concurrent mark sweep GC freed 69649(3MB) AllocSpace objects, 4(246KB) LOS objects, 33% free, 20MB/30MB, paused 1.625ms total 135.317ms
,V/AlarmManager(  887): done {10c026f, *walarm*:com.google.android.intent.action.SEND_IDLE} [111ms]
,I/ActivityManager(  887): Killing 6381:android.process.acore/u0a7 (adj 15): empty #7
,D/BSUtils ( 2671): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/DHCPCD  ( 6893): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6893): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6893): wlan0: sending REQUEST (xid 0xff61d1c0), next in 4.02 seconds
,D/BSUtils ( 2671): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2671): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_6381/cgroup.procs: No such file or directory
,I/vclib   ( 6853): onServiceConnected
,W/Babel   ( 6853): Attempted to change video mute state without an active call.
,D/BSUtils ( 2671): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  887): done {d68e8a7, *alarm*:android.intent.action.TIME_TICK} [263ms]
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 56041(3MB) AllocSpace objects, 37(1256KB) LOS objects, 39% free, 7MB/12MB, paused 669us total 45.033ms
,D/BSUtils ( 2671): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2671): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2671): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2671): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2671): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2671): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2671): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2671): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2671): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2671): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2671): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2671): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2671): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/DHCPCD  ( 6893): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6893): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6893): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 6893): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6893): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6893): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  487): NL - Read 60 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 20
D/TCMD    (  487): Listening for incoming client connection request
,D/DHCPCD  ( 6893): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  887): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  887): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/ModemStatsDSDetect( 1540): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=0
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:10:03 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449753003901], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449753003880]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1540): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1295): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1540): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1540): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1540): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1462): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2671): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6966 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2671): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2671): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2671): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2671): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1462): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2671): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/Central_PollingManager( 1462): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2671): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2671): [debug] > CusSM.onRadioDown
,D/CCE     ( 2671): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2671): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2671): Registering with Alarm Manager to restart CCE
,I/MusicStore( 6966): Database version: 120
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6966): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6966): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6966): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6966): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6966): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6966): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6966): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6966): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@270ac227: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6966): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6966): GMSCore installation verified
,I/ConfigStore( 6966): Config Database version: 1
,I/MediaRouter( 6966): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ConnectivityService(  887): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/MusicLeanback( 6966): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6966): type=WIFI subType= reason=null isConnected=true
,I/art     (  887): Explicit concurrent mark sweep GC freed 18580(946KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.520ms total 126.484ms
,I/NetworkMonitor( 6966): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7010 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6966): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6966): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 6628:com.google.android.gms/u0a16 (adj 15): empty #7
,W/ActivityManager(  887): Application dead when creating service ServiceRecord{3d0ce36a u0 com.google.android.gms/.ads.identifier.service.AdvertisingIdService}
W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_6628/cgroup.procs: No such file or directory
,W/ActivityManager(  887): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 1000ms
,W/ActivityManager(  887): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 4000ms
,W/ActivityManager(  887): Spurious death for ProcessRecord{3d661a2c 0:com.google.android.gms/u0a16}, curProc for 6628: null
,V/Mms     ( 7010): mnc/mcc: 
,V/Mms     ( 7010): tag: int value: recipientLimit - 20
V/Mms     ( 7010): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7010): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7010): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7010): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7010): tag: bool value: enableGroupMms - false
V/Mms     ( 7010):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7010): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7041 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6535:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10057/pid_6535/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7041): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7041): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7041): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Start proc com.google.android.gms for broadcast com.google.android.gms/.mdm.receivers.ConnectivityReceiver: pid=7059 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
I/ActivityManager(  887): Killing 6466:com.android.vending/u0a32 (adj 15): empty #7
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524295
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_6466/cgroup.procs: No such file or directory
,W/ResourcesManager( 7059): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7059): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7059): VM with version 2.1.0 has multidex support
I/MultiDex( 7059): install
I/MultiDex( 7059): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7059): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7059): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7059): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c6e33c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7059): Installed default security provider GmsCore_OpenSSL
,I/CheckinService( 7059): Checkin interval check for package: unspecified last checkin: 1449752921245 min interval config: 0 actual interval: 84696
,D/NativeLibraryUtils( 7059): Install completed successfully. count=14 extracted=0
,I/CheckinService( 7059): Disabling old GoogleServicesFramework version
,I/CheckinService( 7059): Checking schedule, now: 1449753005987 next: 1449752951215
I/CheckinService( 7059): active receiver: enabled
,I/CheckinService( 7059): Preparing to send checkin request
,I/EventLogService( 7059): Accumulating logs since 1449752917265
,I/iu.SyncManager( 7059): SYNC; picasa accounts
,D/NetworkLogImpl( 7059): Loaded NetworkSpeedPredictor
,I/iu.Environment( 7059): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/art     ( 7059): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7059): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/iu.UploadsManager( 7059): num queued entries: 0
,I/iu.UploadsManager( 7059): num updated entries: 0
,I/iu.SyncManager( 7059): NEXT; no task
,I/jxcore-log( 6761): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6761): 
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7104 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 7059): Checkin reason type: 8 attempt count: 1
,D/WifiService(  887): New client listening to asynchronous messages
,E/ActivityThread( 7059): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7126 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6853): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7147 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6829:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10008/pid_6829/cgroup.procs: No such file or directory
,W/ResourcesManager( 7147): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7147): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/MultiDex( 7147): VM with version 2.1.0 has multidex support
I/MultiDex( 7147): install
I/MultiDex( 7147): VM has multidex support, MultiDex support library is disabled.
D/Tethering(  887): MasterInitialState.processMessage what=3
D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2671): now: 199888 ,futureTime: 9223372036854775807
D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2671): now: 199888 ,futureTime: 9223372036854775807
D/PollingManager( 2671): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2671): now: 199891 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1462): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2671): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/Central_PollingManager( 1462): now: 199894 ,futureTime: 86475005
D/Central_PollingManager( 1462): Polling alarm set to expire at: 86475005 Current Time: 199894
D/OtaApp  ( 2671): [debug] > PollingManagerService, now: 199895 ,futureTime: 4938034
I/NetworkMonitor( 6966): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2671): [debug] > Polling alarm set to expire at: 4938034 Current Time: 199896
,D/MMApiProvisionService( 2671): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2671): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2671): createDeviceIdOrLogin update_device
,D/Checkin ( 2671): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2671): Not proxy app, so login/provision not allowed
,V/JNIHelp ( 7147): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 4803(213KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 656us total 33.660ms
,D/MMApiProvisionService( 2671): isDeviceProvisioned: deviceId = 2072049230914535424
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7126): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7126): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ActivityThread( 7147): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ContextImpl( 7126): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/System  ( 7147): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@712c5dc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7147): Installed default security provider GmsCore_OpenSSL
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7126): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7126): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7126):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7126):   adb logcat -s GAv4
,I/art     ( 7147): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7147): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/GAv4    ( 7126): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7126): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 2671): Explicit concurrent mark sweep GC freed 15079(815KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.142ms total 98.059ms
,D/CCE     ( 2671): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2671): createDeviceIdOrLogin update_device
,W/GAv4    ( 7126): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/Checkin ( 2671): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2671): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2671): set mOutstandingReq to true.
I/ Nonce  ( 2671):  Nonce getNonce 
I/ Nonce  ( 2671):  Nonce Request 
I/ Nonce  ( 2671):  Nonce execute Request 
,D/MMApiProvisionService( 2671): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2671): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2671): createDeviceIdOrLogin update_device
,D/Checkin ( 2671): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2671): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2671): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2671): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2671): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2671): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2671): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2671): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2671): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2671): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2671): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2671): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/NativeLibraryUtils( 7147): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  298): Instantiating CDM.
I/WVCdm   (  298): CdmEngine::OpenSession
,I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/art     (  887): Explicit concurrent mark sweep GC freed 13867(654KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.811ms total 164.913ms
,I/art     (  887): WaitForGcToComplete blocked for 93.783ms for cause HeapTrim
,D/MMApiWebService( 2671): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb502b000
E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb502b000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb54fc960
,D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb8520e98, dataLength=8
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb85cf4e0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb861ad98, idLength=0xb1412730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
,D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=445754808
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb85cf4e0
D/DrmWidevineDash(  298): message_length=1591, signature=0xb84fa3a8, signature_length=2973837076
,D/MMApiWebService( 2671): generating token using payload instead of using session token
,D/ Nonce  ( 2671):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2671): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2671): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  298): CdmEngine::CloseSession
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,I/WebViewFactory( 7126): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7126): Time to load native libraries: 1 ms (timestamps 613-614)
I/LibraryLoader( 7126): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7126): Binding Chromium to main looper Looper (main, tid 1) {5015e0c}
,I/LibraryLoader( 7126): Expected native library version number "",actual native library version number ""
I/chromium( 7126): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7126): Initializing chromium process, singleProcess=true
W/art     ( 7126): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7126): ApplicationContext is null in ApplicationStatus
,W/chromium( 7126): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7126): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7126): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7126): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7126): Local Branch: 
I/Adreno-EGL( 7126): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7126): Local Patches: NONE
I/Adreno-EGL( 7126): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7126): Requires BLUETOOTH permission
,I/NSApplication( 7126): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7216 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 6966:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  316): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.657ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.128ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.600ms
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_6966/cgroup.procs: No such file or directory
,I/dex2oat ( 7236): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7236): dex2oat took 183.737ms (threads: 4)
,I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7147): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7147): Local Branch: 
I/Adreno-EGL( 7147): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7147): Local Patches: NONE
I/Adreno-EGL( 7147): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7245 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7010:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_7010/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7147): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7147): Local Branch: 
I/Adreno-EGL( 7147): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7147): Local Patches: NONE
I/Adreno-EGL( 7147): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 7245): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7266 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ Nonce  ( 2671):  Nonce Reponse 
D/        ( 2671): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"2ab7c965-340f-4a90-8358-e53c7c5b37ce"}
D/MMApiWSBase( 2671): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2671):  Nonce Handle Reponse 
D/MMApiProvisionService( 2671): mOutstandingReq set to false
,I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7147): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7147): Local Branch: 
I/Adreno-EGL( 7147): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7147): Local Patches: NONE
I/Adreno-EGL( 7147): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7287 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7104:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7147): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7147): Local Branch: 
I/Adreno-EGL( 7147): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7147): Local Patches: NONE
I/Adreno-EGL( 7147): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/art     ( 7245): Suspending all threads took: 5.586ms
,D/MMApiProvisionService( 2671):  pTime 1449671329422 sExp 172742 cTime 1449753008704 tTime 1449844071422
D/MMApiProvisionService( 2671):  No login Required 
,I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
,I/ContactLocale( 7266): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb502b000
E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb502b000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
,D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
I/ActivityManager(  887): Killing 7041:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb1412960
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb85489d0, dataLength=8
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb85cf4e0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb861add8, idLength=0xb1312730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=1019242786
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb85cf4e0
D/DrmWidevineDash(  298): message_length=1626, signature=0xb8523ff8, signature_length=2972788500
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7104/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7041/cgroup.procs: No such file or directory
,I/MusicStore( 7287): Database version: 120
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7287): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  298): CdmEngine::CloseSession
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,W/DataUsage( 2671): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2671): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7287): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7287): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 7059): Classify the device as Phone.
,W/ResourcesManager( 7287): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7287): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7287): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AlarmManager(  887): send {679d139, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/ActivityThread( 7287): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7287): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@270ac227: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7287): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7287): GMSCore installation verified
,I/ConfigStore( 7287): Config Database version: 1
,I/CheckinTask( 7059): Sending checkin request (9553 bytes)
,I/art     ( 6600): Explicit concurrent mark sweep GC freed 1495(64KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 358us total 25.522ms
,I/MediaRouter( 7287): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7287): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7287): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7287): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7333 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7287): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7287): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 6853:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_6853/cgroup.procs: No such file or directory
,V/Mms     ( 7333): mnc/mcc: 
,V/Mms     ( 7333): tag: int value: recipientLimit - 20
V/Mms     ( 7333): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7333): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7333): tag: int value: maxSubjectLength - 80
V/Mms     ( 7333): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7333): tag: bool value: enableGroupMms - false
,V/Mms     ( 7333):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7333): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 7059): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7359 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,E/ActivityThread( 7059): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  887): Explicit concurrent mark sweep GC freed 7903(378KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.525ms total 122.608ms
,I/ActivityManager(  887): Killing 7126:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7359): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_7126/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7359): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7359): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 7059): Checkin interval check for package: unspecified last checkin: 1449752921245 min interval config: 0 actual interval: 88767
,I/ActivityManager(  887): Killing 7216:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7377 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_7216/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 7059): Classify the device as Phone.
,I/CheckinTask( 7059): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7059): Checking schedule, now: 1449753010226 next: 1450354147210
I/CheckinService( 7059): active receiver: disabled
,I/CheckinService( 7059): Checking schedule, now: 1449753010245 next: 1450354147210
,I/CheckinService( 7059): active receiver: disabled
,D/CheckinService( 7059): Recording last checkin time for package unspecified as 1449753010250
,I/ActivityManager(  887): Killing 7266:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  887): Killing 7245:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7266/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7245/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7400 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  887): Killing 7287:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_7287/cgroup.procs: No such file or directory
,W/ResourcesManager( 7400): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7400): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7400): MmsConfig.loadMmsSettings
I/Babel_SMS( 7400): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7400): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7400): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7400): MmsConfig.loadFromResources
,E/Babel_SMS( 7400): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7400): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7400): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7400): startup - clean
,I/Babel   ( 7400): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7431 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7400): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7400): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7400): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7400): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7400): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7400): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7400): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7400): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7400): onServiceConnected
,W/Babel   ( 7400): Attempted to change video mute state without an active call.
,I/GAv4    ( 7431): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7431):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7431):   adb logcat -s GAv4
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7431): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7431): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7431): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7431): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7431): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7400): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 7333:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7431): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7431): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_7333/cgroup.procs: No such file or directory
,I/WebViewFactory( 7431): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7431): Time to load native libraries: 1 ms (timestamps 4681-4682)
I/LibraryLoader( 7431): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7431): Binding Chromium to main looper Looper (main, tid 1) {5015e0c}
,I/LibraryLoader( 7431): Expected native library version number "",actual native library version number ""
,I/chromium( 7431): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7431): Initializing chromium process, singleProcess=true
,W/art     ( 7431): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7431): ApplicationContext is null in ApplicationStatus
,W/chromium( 7431): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7431): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7431): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7431): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7431): Local Branch: 
I/Adreno-EGL( 7431): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7431): Local Patches: NONE
I/Adreno-EGL( 7431): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7431): Requires BLUETOOTH permission
,I/NSApplication( 7431): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7503 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7359:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7359/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7527 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7377:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7377/cgroup.procs: No such file or directory
,W/ResourcesManager( 7527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7550 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  316): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 22.219ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 23.065ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.726ms
,I/ActivityManager(  887): Killing 7431:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7550): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  887): failed to kill 1 processes for processgroup 7431
I/ActivityManager(  887): Killing 7400:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2671): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7400/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2671): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2671): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2671): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2671): onServiceConnected()
D/GetNotificationsWS( 2671): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2671): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2671): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1751): callingUid 10016, callindPid: 1751
,E/MDM     ( 1751): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7059): Restart initialization of location
,D/AuthorizationBluetoothService( 1751): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7594 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/IcingInternalCorpora( 7059): getNumBytesRead when not calculated.
,I/art     ( 1751): Explicit concurrent mark sweep GC freed 87696(4MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 14MB/24MB, paused 2.086ms total 135.213ms
W/GCoreFlp( 1751): No location to return for getLastLocation()
,W/FusedLocationProvider( 1751): location=null
,E/DataBuffer( 1751): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@257dbb08)
,E/DataBuffer( 1751): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@35b542a1)
E/DataBuffer( 1751): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2009cc6)
E/DataBuffer( 1751): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@112b4487)
E/DataBuffer( 1751): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5b77fb4)
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7620 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7620): Database version: 120
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7620): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7620): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7620): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:33000 mC
,W/ResourcesManager( 7620): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7620): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7620): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7620): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7620): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@270ac227: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7620): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7620): GMSCore installation verified
,I/ConfigStore( 7620): Config Database version: 1
,I/art     (  887): Explicit concurrent mark sweep GC freed 12472(632KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.489ms total 111.479ms
,I/MediaRouter( 7620): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7620): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7620): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7620): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7658 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7620): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7620): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7658): mnc/mcc: 
,V/Mms     ( 7658): tag: int value: recipientLimit - 20
,V/Mms     ( 7658): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7658): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7658): tag: int value: maxSubjectLength - 80
V/Mms     ( 7658): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7658): tag: bool value: enableGroupMms - false
V/Mms     ( 7658):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7658): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7689 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7503:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_7503/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7689): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7689): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7689): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 7527:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7527/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7550:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7550/cgroup.procs: No such file or directory
,I/CheckinService( 7059): Checkin interval check for package: unspecified last checkin: 1449753010250 min interval config: 0 actual interval: 3928
,I/CheckinService( 7059): Checkin interval check for package: unspecified last checkin: 1449753010250 min interval config: 0 actual interval: 3932
,I/CheckinService( 7059): Checking schedule, now: 1449753014195 next: 1449753040210
I/CheckinService( 7059): active receiver: disabled
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7709 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 7059): Checking schedule, now: 1449753014262 next: 1449753040210
,I/CheckinService( 7059): active receiver: disabled
,W/ResourcesManager( 7709): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7709): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7709): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7709): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7709): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7709): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7709): MmsConfig.loadFromResources
,E/Babel_SMS( 7709): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7709): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7709): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7709): startup - clean
,I/Babel   ( 7709): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7736 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7709): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7709): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7709): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7709): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7709): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7709): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7709): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7709): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7709): onServiceConnected
W/Babel   ( 7709): Attempted to change video mute state without an active call.
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7736): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7736): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7736): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7736):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7736):   adb logcat -s GAv4
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7736): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  281): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7736): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7736): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7709): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 7620:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7736): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7736): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_7620/cgroup.procs: No such file or directory
,I/WebViewFactory( 7736): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7736): Time to load native libraries: 1 ms (timestamps 8307-8308)
I/LibraryLoader( 7736): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7736): Binding Chromium to main looper Looper (main, tid 1) {5015e0c}
,I/LibraryLoader( 7736): Expected native library version number "",actual native library version number ""
,I/chromium( 7736): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7736): Initializing chromium process, singleProcess=true
W/art     ( 7736): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7736): ApplicationContext is null in ApplicationStatus
,W/chromium( 7736): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7736): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7736): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7736): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7736): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7736): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7736): Local Branch: 
I/Adreno-EGL( 7736): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7736): Local Patches: NONE
I/Adreno-EGL( 7736): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7736): Starting up...
,W/AudioManagerAndroid( 7736): Requires BLUETOOTH permission
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7807 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7658:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_7658/cgroup.procs: No such file or directory,
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7831 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 7689:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7689/cgroup.procs: No such file or directory
,W/ResourcesManager( 7831): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7851 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7147:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,D/EmailService.MarketingOptInSetter( 2671): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_7147/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7594:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7594/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2671): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2671): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2671): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2671): onServiceConnected()
D/GetNotificationsWS( 2671): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2671): unbindWebServices(): un-registering our AIDL callback...
,D/LocationInitializer( 7059): Restart initialization of location
,I/PushService( 2671): started with background data enabled, making sure notification mechanism is enabled
,D/AuthorizationBluetoothService( 1751): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1751): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2671): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2671): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2671): [debug] > In cancelAnyPendingIntentSetPreviously
,W/GCoreFlp( 1751): No location to return for getLastLocation()
,W/FusedLocationProvider( 1751): location=null
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  887): done {679d139, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6864ms]
,D/OtaApp  ( 2671): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2671): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2671): publish the event [tag = MOT_OTA event name = LOG]
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,D/OtaApp  ( 2671): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2671): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2671): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7894 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2671): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2671): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2671): publish the event [tag = MOT_OTA event name = LOG]
,I/ContactLocale( 7851): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/OtaApp  ( 2671): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2671): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2671): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1421): onFinishInput()
,W/IInputConnectionWrapper( 6761): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7894): Register our PhoneStateListener
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@21b56731
,I/LaunchCheckinHandler(  887): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,237
,V/SetupWizard( 7894): Connected to Gservices successfully
,I/GCoreNlp( 1751): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1576): Deferring update until onResume
,I/art     (  887): Explicit concurrent mark sweep GC freed 19321(972KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.406ms total 120.398ms
,I/ActivityManager(  887): Killing 7709:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7709/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7919 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  316): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 23.122ms
,D/GCM     ( 1751): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.770ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 24.442ms
,D/GCM     ( 1751): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7943 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7736:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_7736/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7968 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7985 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  887): Killing 7807:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  887): Killing 7831:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_7807/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7831/cgroup.procs: No such file or directory
,W/ResourcesManager( 7985): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7985): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7985): MmsConfig.loadMmsSettings
I/Babel_SMS( 7985): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7985): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7985): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7985): MmsConfig.loadFromResources
,E/Babel_SMS( 7985): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7985): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7985): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7985): startup - clean
,I/Babel   ( 7985): deleted: false for 0
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8018 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7985): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7985): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7985): Unsupported mime video/mpeg2
,W/asset   ( 8018): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8018): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8018): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8018): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7985): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7985): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7985): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7985): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7985): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 7059): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7059): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@27fbe64d new=com.google.android.velvet.VelvetApplication@27fbe64d
,I/UpdateIcingCorporaServi( 7943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8050 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7985): onServiceConnected
W/Babel   ( 7985): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7985): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7985): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 8050): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 7059): Storage manager: low false usage 1.75MB avail 3.15GB capacity 4.85GB
,I/UpdateIcingCorporaServi( 7943): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,I/ActivityManager(  887): Killing 7919:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7985): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7985): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7985): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7919/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8089 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7894:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/Icing   ( 7059): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7894/cgroup.procs: No such file or directory
,I/art     ( 6600): Explicit concurrent mark sweep GC freed 3208(126KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 387us total 27.837ms
,I/Icing   ( 7059): Internal init done: storage state 0
,I/Icing   ( 7059): Post-init done
,I/Icing   ( 7059): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 8089): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8089): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8089): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8089): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 8089): Skipping gmscore version check
D/Finsky  ( 8089): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8089): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 8089): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8089): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  887): Killing 7968:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_7968/cgroup.procs: No such file or directory
,D/TaskPersister(  887): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 7059): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 7059): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7059): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  887): Killing 8018:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_8018/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7943:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_7943/cgroup.procs: No such file or directory
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:33000 mC
,I/CheckinService( 7059): Done disabling old GoogleServicesFramework version
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=300, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310807, SEQNUM=4503, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-490, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=290, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311232, SEQNUM=4505, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-521, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1751): disconnect managed GoogleApiClient
,V/AlarmManager(  887): send {5ff4e21, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  887): send {be33461, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  887): done {5ff4e21, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
V/AlarmManager(  887): done {be33461, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [19ms]
,I/CheckinService( 7059): Checkin interval check for package: unspecified last checkin: 1449753010250 min interval config: 0 actual interval: 42894
,I/CheckinService( 7059): Checking schedule, now: 1449753053158 next: 1449753040210
I/CheckinService( 7059): active receiver: enabled
,I/CheckinService( 7059): Preparing to send checkin request
I/EventLogService( 7059): Accumulating logs since 1449753006262
,I/CheckinRequestBuilder( 7059): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 7059): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  887): Explicit concurrent mark sweep GC freed 15296(802KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.586ms total 112.453ms
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8177 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8177): VM with version 2.1.0 has multidex support
,I/MultiDex( 8177): install
I/MultiDex( 8177): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8177): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8177): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8177): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@712c5dc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8177): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1751): callingUid 10016, callindPid: 1751
,E/MDM     ( 1751): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7059): Restart initialization of location
D/AuthorizationBluetoothService( 1751): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1751): No location to return for getLastLocation()
W/FusedLocationProvider( 1751): location=null
,I/art     ( 8177): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8177): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8177): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  298): Instantiating CDM.
,I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
,D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb54fc960
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb8554d00, dataLength=8
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb85cf4e0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb861adb8, idLength=0xb1412730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=758631612
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb85cf4e0
D/DrmWidevineDash(  298): message_length=1591, signature=0xb84fa3a8, signature_length=2973837076
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  298): CdmEngine::CloseSession
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8220): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8220): dex2oat took 63.529ms (threads: 4)
,I/Adreno-EGL( 8177): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8177): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8177): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8177): Local Branch: 
I/Adreno-EGL( 8177): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8177): Local Patches: NONE
I/Adreno-EGL( 8177): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8177): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8177): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8177): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8177): Local Branch: 
I/Adreno-EGL( 8177): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8177): Local Patches: NONE
I/Adreno-EGL( 8177): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8177): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8177): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8177): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8177): Local Branch: 
I/Adreno-EGL( 8177): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8177): Local Patches: NONE
I/Adreno-EGL( 8177): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8177): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8177): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8177): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8177): Local Branch: 
I/Adreno-EGL( 8177): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8177): Local Patches: NONE
I/Adreno-EGL( 8177): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
,D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  298): hlos api version =  9
,D/DrmWidevineDash(  298): tz api version =  8
,D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb55fc960
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb851fc28, dataLength=8
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb85cf4e0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb861add8, idLength=0xb1412730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=2480305488
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb85cf4e0
D/DrmWidevineDash(  298): message_length=1626, signature=0xb8523ff8, signature_length=2973837076
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  298): CdmEngine::CloseSession
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 7059): Classify the device as Phone.
,I/CheckinTask( 7059): Sending checkin request (9561 bytes)
,I/CheckinRequestBuilder( 7059): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 7059): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 7059): Classify the device as Phone.
,I/CheckinTask( 7059): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7059): Checking schedule, now: 1449753057357 next: 1450354194352
,I/CheckinService( 7059): active receiver: disabled
,D/CheckinService( 7059): Recording last checkin time for package unspecified as 1449753057380
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8252 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8252): Register our PhoneStateListener
,V/SetupWizard( 8252): Connected to Gservices successfully
,D/GCM     ( 1751): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  887): Killing 8050:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  887): Killing 7851:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_8050/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7851/cgroup.procs: No such file or directory
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8282 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@285bf5fb
,I/GCoreNlp( 1751): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,I/Launcher( 1576): Deferring update until onResume
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8312 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8334 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8089:com.android.vending/u0a32 (adj 15): empty #7
,I/art     (  316): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 22.723ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 22.677ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.827ms
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_8089/cgroup.procs: No such file or directory
,W/ResourcesManager( 7985): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7985): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8334): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8361 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8252:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_8252/cgroup.procs: No such file or directory
,W/asset   ( 8361): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8361): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 8361): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 7059): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7059): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 8282): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1576): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@27fbe64d new=com.google.android.velvet.VelvetApplication@27fbe64d
,I/Icing   ( 7059): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8392 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8392): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8282): UpdateCorporaTask done [took 163 ms] updated apps [took 163 ms] 
,I/art     (  887): Explicit concurrent mark sweep GC freed 17384(893KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.522ms total 115.288ms
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8421 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8177:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_8177/cgroup.procs: No such file or directory
,D/Finsky  ( 8421): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8421): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8421): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8421): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8421): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8421): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8421): Skipping gmscore version check
,D/Finsky  ( 8421): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8421): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  887): Killing 8312:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_8312/cgroup.procs: No such file or directory
,I/Icing   ( 7059): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 7059): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  887): Killing 8361:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_8361/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7985:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7985/cgroup.procs: No such file or directory
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1421): run()
,I/Keyboard.Facilitator( 1421): flushDynamicLanguageModels()
,I/ConfigService( 1751): onCreate
,I/ConfigService( 1751): onDestroy
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311449, SEQNUM=4533, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-605, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC

```
