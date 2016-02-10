#### Test 58752353dc32d9f_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6187): 
D/AndroidRuntime( 6187): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6187): CheckJNI is OFF
D/AndroidRuntime( 6187): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6206 uid=10530 gids={50530, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6187): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6206): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6206): Time to load native libraries: 2 ms (timestamps 7468-7470)
I/LibraryLoader( 6206): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6206): Binding Chromium to main looper Looper (main, tid 1) {3ecf51cb}
I/LibraryLoader( 6206): Expected native library version number "",actual native library version number ""
,I/chromium( 6206): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6206): Initializing chromium process, singleProcess=true
W/art     ( 6206): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6206): ApplicationContext is null in ApplicationStatus
,W/chromium( 6206): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6206): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6206): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6206): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6206): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6206): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6206): Local Branch: 
I/Adreno-EGL( 6206): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6206): Local Patches: NONE
I/Adreno-EGL( 6206): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37a489a5:true
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{3d1f1096 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6206): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6206): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6206): CordovaWebView is running on device made by: motorola
,W/art     ( 6206): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6206): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6206): Render dirty regions requested: true
,D/Atlas   ( 6206): Validating map...
,W/chromium( 6206): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6206): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6206): Enabling debug mode 0
,I/Keyboard.Facilitator( 1414): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1069
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +984ms (total +1s69ms)
,W/IInputConnectionWrapper( 6206): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6206): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6206): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6206): Cannot call determinedVisibility() - never saw a connection for the pid: 6206
,D/JsMessageQueue( 6206): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6206): JniHelper::setJavaVM(0xb8c27310), pthread_self() = -1191451568
,I/chromium( 6206): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6206): Initializing JXcore engine
W/jxcore-log( 6206): JXcore engine is ready
,W/Thread-727( 6254): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10530 path="socket:[5620]" dev="sockfs" ino=5620 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-727( 6254): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10530 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-727( 6254): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10530 path="socket:[7584]" dev="sockfs" ino=7584 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-727( 6254): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10530 path="socket:[26183]" dev="sockfs" ino=26183 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6206): Starting JXcore engine
,W/jxcore-log( 6206): Platform android
W/jxcore-log( 6206): 
,W/jxcore-log( 6206): Process ARCH arm
W/jxcore-log( 6206): 
,I/jxcore-log( 6206): JXcore Cordova bridge is ready!
I/jxcore-log( 6206): 
,W/jxcore-log( 6206): JXcore engine is started
,I/jxcore-log( 6206): Toggling radios to true
I/jxcore-log( 6206): 
,D/BluetoothAdapter( 6206): enable(): BT is already enabled..!
,D/WifiService(  881): New client listening to asynchronous messages
,D/WifiService(  881): setWifiEnabled: true pid=6206, uid=10530
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6206): Radios toggled
I/jxcore-log( 6206): 
I/jxcore-log( 6206): My device name is: motorola-XT1072
I/jxcore-log( 6206): 
,I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  307): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  307):  STA Disconnected !!
I/MDMCTBK (  307): checkDefaultInst, current pid is = 307
I/MDMCTBK (  307): checkDefaultInst, pid match
I/MDMCTBK (  307): get_property_value, Enter
I/MDMCTBK (  307): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  307): get_property_value, Exit
I/MDMCTBK (  307): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  307): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  307): set_property_value, Enter
I/MDMCTBK (  307): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  484): NL - Read 1004 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 68 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 68 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
,I/MDMCTBK (  307): set_property_value, Values updated in the property file Successfully,
D/Tethering(  881): InitialState.processMessage what=4
I/MDMCTBK (  307): set_property_value, Exit
I/MDMCTBK (  307): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  307): MdmCutbackHndler,Wifi disconnected !!!,
I/MDMCTBK (  307): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0,
I/MDMCTBK (  307): set_property_value, Enter
I/MDMCTBK (  307): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/MDMCTBK (  307): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  307): set_property_value, Exit
E/MDMCTBK (  307): MdmCutbackHndler,Airplane Mode Enabled !! =1
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881):  0
D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  307): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  307): Event received = CTRL-EVENT-REGDOM-CHANGE
I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  307): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
,E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  304): Clearing all IP addresses on wlan0
,D/TCMD    (  484): NL - Read 60 bytes from update socket.
D/TCMD    (  484): NL - ignore NL message, type = 21
D/TCMD    (  484): Listening for incoming client connection request
,V/NativeCrypto( 1747): Read error: ssl=0xb8eaeba8: I/O error during system call, Connection timed out
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,V/NativeCrypto( 1747): SSL shutdown failed: ssl=0xb8eaeba8: I/O error during system call, Broken pipe
,D/WifiMetrics(  881): connected time updated 220150
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6270 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524292
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524292
D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  881): Start Disconnecting Watchdog 1
,D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  307): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  307): Event received = CTRL-EVENT-SCAN-STARTED 
,E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  881): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=null
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/CommandListener(  304): Clearing all IP addresses on wlan0
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6270): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6297 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.223ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 18.868ms
,I/ActivityManager(  881): Killing 5836:android.process.acore/u0a7 (adj 15): empty #7
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.834ms
,D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  307): Event received = CTRL-EVENT-SCAN-RESULTS 
,I/wpa_supplicant( 1435): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  307): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  307): Event received = Trying to associate with
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  307): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  881): [1,455,113,698,665 ms] noteScanEnd no scan source
D/WifiMonitor(  881): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1435): DSDS: eapol_sm_notify_config config->sim_num = 1
D/TCMD    (  484): NL - Read 56 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@89db84f sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info0x
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_5836/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6297): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  484): NL - Read 312 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 192 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 68 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 1004 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
,D/TCMD    (  484): NL - Read 80 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 80 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
D/TCMD    (  484): NL - Read 68 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
I/wpa_supplicant( 1435): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  307): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  307): Event received = Associated with c0:ff:d4
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  307): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  307): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1435): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  307): Event received = WPA: Key negotiation com
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  307): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  307):  STA Connected !!
D/TCMD    (  484): NL - Read 1004 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
,E/MDMCTBK (  307): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  307): get_freq !!, resp=2412
I/MDMCTBK (  307): get_freq !!, Strip data
I/MDMCTBK (  307): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  307): checkDefaultInst, current pid is = 307
I/MDMCTBK (  307): checkDefaultInst, pid match
I/MDMCTBK (  307): get_property_value, Enter
I/MDMCTBK (  307): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  307): get_property_value, Exit
I/MDMCTBK (  307): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  307): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  307): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  307): set_property_value, Enter
I/MDMCTBK (  307): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  307): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  307): set_property_value, Exit
I/MDMCTBK (  307): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
,I/MDMCTBK (  307): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  307): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  307): checkDefaultInst, current pid is = 307
I/MDMCTBK (  307): checkDefaultInst, pid match
I/MDMCTBK (  307): get_property_value, Enter
I/MDMCTBK (  307): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  307): get_property_value, Exit
I/MDMCTBK (  307): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1218798248
I/MDMCTBK (  307): return from set_get_from_wpa_supplicant
I/MDMCTBK (  307): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  307): set_property_value, Enter
I/MDMCTBK (  307): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  307): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  307): set_property_value, Exit
E/MDMCTBK (  307): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  307): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  307): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/MDMCTBK (  307): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  307): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  307): , reply_len: 3, ret: 0
E/MDMCTBK (  307): MdmCutbackHndler, resp=OK
E/MDMCTBK (  307): 
D/MDMCTBK (  307): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  881): Network connection established
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  881): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  881): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  881): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  881): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  304): Setting iface cfg
E/WifiStateMachine(  881): Start Dhcp Watchdog 2
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend false
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  881): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@290fa783 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@290fa783 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6297): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6297): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6297): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6297): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6297): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6297): MmsConfig.loadFromResources
E/Babel_SMS( 6297): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6297): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6297): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6297): startup - clean
,I/Babel   ( 6297): deleted: false for 0
,E/DHCPCD  ( 6327): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 6327): version 5.5.6 starting
,E/DHCPCD  ( 6327): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6327): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6327): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/art     ( 6297): Suspending all threads took: 7.186ms
,W/VideoCapabilities( 6297): Unrecognized profile 2130706433 for video/avc
,D/DHCPCD  ( 6327): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6327): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6327): wlan0: sending REQUEST (xid 0x21b3c771), next in 4.18 seconds
,W/AudioCapabilities( 6297): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6297): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6297): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6297): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6297): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6297): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6297): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Killing 5994:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_5994/cgroup.procs: No such file or directory
,I/vclib   ( 6297): onServiceConnected
W/Babel   ( 6297): Attempted to change video mute state without an active call.
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,V/AlarmManager(  881): send {2c0ad050, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {19f0fd7, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6345 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  881): done {2c0ad050, *alarm*:android.intent.action.TIME_TICK} [93ms]
,I/GAv4    ( 6345): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6345):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6345):   adb logcat -s GAv4
,W/GAv4    ( 6345): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/DHCPCD  ( 6327): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,W/GAv4    ( 6345): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6345): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/DHCPCD  ( 6327): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6327): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6327): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6327): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6327): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  484): NL - Read 60 bytes from update socket.
D/TCMD    (  484): NL - ignore NL message, type = 20
D/TCMD    (  484): Listening for incoming client connection request
D/DHCPCD  ( 6327): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,V/AlarmManager(  881): done {19f0fd7, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [275ms]
,I/ActivityManager(  881): Killing 5927:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_5927/cgroup.procs: No such file or directory
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  881): MasterInitialState.processMessage what=3
D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1472): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2611): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6393 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1472): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1472): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2611): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2611): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2611): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2611): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2611): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2611): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2611): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2611): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2611): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2611): [debug] > CusSM.onRadioDown
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): WifiStateMachine DHCP successful
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  881): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  881): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  881): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  881): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  881): Adding Route [fe80::/64 -> :: wlan0] to network 101
,E/WifiStateMachine(  881): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  881): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  881): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  881): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881):    accepting network in place of null
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  881): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  881): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/MusicStore( 6393): Database version: 120
I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6393): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6393): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6393): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6393): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6393): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6393): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6393): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6393): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29e211d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6393): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6393): GMSCore installation verified
,I/ConfigStore( 6393): Config Database version: 1
,I/MediaRouter( 6393): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6393): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6393): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6393): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6438 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6393): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6393): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6029:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_6029/cgroup.procs: No such file or directory
,V/Mms     ( 6438): mnc/mcc: 
V/Mms     ( 6438): tag: int value: recipientLimit - 20
V/Mms     ( 6438): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6438): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6438): tag: int value: maxSubjectLength - 80
V/Mms     ( 6438): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6438): tag: bool value: enableGroupMms - false
V/Mms     ( 6438):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6438): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6464 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6297:com.google.android.talk/u0a70 (adj 15): empty #7
,D/ConnectivityService(  881): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6297/cgroup.procs: No such file or directory
,I/art     (  881): Explicit concurrent mark sweep GC freed 43114(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.657ms total 131.438ms
,D/PhoneMonitor( 6464): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6464): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 14:15:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455113702948], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455113702929]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
,D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1532): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1532): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1956): CM callback handler got msg 524290
,D/MobileConnectivityChangeReceiver( 6464): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6270:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6270/cgroup.procs: No such file or directory
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1455113486419 min interval config: 0 actual interval: 216789
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6486 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1956): Checking schedule, now: 1455113703335 next: 1455113516300
I/CheckinService( 1956): active receiver: enabled
,I/CheckinService( 1956): Preparing to send checkin request
I/EventLogService( 1956): Accumulating logs since 1455113478359
,I/CheckinRequestBuilder( 1956): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6513 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6530 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6513): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6530): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 6513): VM with version 2.1.0 has multidex support
I/MultiDex( 6513): install
I/MultiDex( 6513): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6513): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6513): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6513): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12dab67f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6513): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 6530): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6530): MmsConfig.loadMmsSettings
I/Babel_SMS( 6530): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6530): MmsConfig.loadFromDatabase
I/art     ( 6513): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6513): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Babel_SMS( 6530): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6530): MmsConfig.loadFromResources
,E/Babel_SMS( 6530): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6530): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 6513): Install completed successfully. count=14 extracted=0
,W/Settings( 6530): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6530): startup - clean
,I/Babel   ( 6530): deleted: false for 0
,D/WVCdm   (  309): Instantiating CDM.
,I/WVCdm   (  309): CdmEngine::OpenSession
,I/WVCdm   (  309): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  309): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  309): Service_Initialize: starts!
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,D/QSEECOMAPI: (  309): Loaded image: APP id = 3
,D/DrmWidevineDash(  309): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffb000
E/DrmWidevineDash(  309): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffb000
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  309): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: starts! SID=0xb0eab960
D/DrmWidevineDash(  309): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: starts! randomData=0xb90ad928, dataLength=8
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb90a35a0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  309): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  309): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  309): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  309): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: starts! deviceID=0xb9179790, idLength=0xbec9e2b0
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  309): PrepareKeyRequest: nonce=2408507190
D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb90ac500
D/DrmWidevineDash(  309): message_length=1591, signature=0xb90b3ca0, signature_length=3200901780
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6570 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  309): CdmEngine::CloseSession
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  309): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  309): L3 Terminate.
D/DrmWidevineDash(  309): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  309): Service_Uninitialize: starts!
D/QSEECOMAPI: (  309): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  309): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  309): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_Terminate: ends! returns 0
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  881): MasterInitialState.processMessage what=3
D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2611): now: 297719 ,futureTime: 9223372036854775807
D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2611): now: 297719 ,futureTime: 9223372036854775807
D/PollingManager( 2611): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2611): now: 297720 ,futureTime: 9223372036854775807
D/OtaApp  ( 2611): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1472): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/OtaApp  ( 2611): [debug] > PollingManagerService, now: 297724 ,futureTime: 16327932
D/OtaApp  ( 2611): [debug] > Polling alarm set to expire at: 16327932 Current Time: 297725
,D/OtaApp  ( 2611): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2611): [debug] > CusSM.onRadioUp
D/Central_PollingManager( 1472): now: 297729 ,futureTime: 86475176
D/Central_PollingManager( 1472): Polling alarm set to expire at: 86475176 Current Time: 297729
D/OtaApp  ( 2611): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2611): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2611): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2611): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2611): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2611): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2611): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
I/NetworkMonitor( 6393): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2611): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MMApiProvisionService( 2611): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2611): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2611): createDeviceIdOrLogin update_device
D/Checkin ( 2611): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2611): Not proxy app, so login/provision not allowed
,W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,D/MMApiProvisionService( 2611): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2611): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2611): createDeviceIdOrLogin update_device
,D/Checkin ( 2611): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2611): isDeviceProvisioned: deviceId = 2072049230914535424
,W/AudioCapabilities( 6530): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6530): Unsupported mime video/mpeg2
,D/MMApiProvisionService( 2611): set mOutstandingReq to true.
I/ Nonce  ( 2611):  Nonce getNonce 
,I/ Nonce  ( 2611):  Nonce Request 
I/ Nonce  ( 2611):  Nonce execute Request 
,D/MMApiWebService( 2611): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2611): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2611): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2611): createDeviceIdOrLogin update_device
,D/Checkin ( 2611): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2611): Not proxy app, so login/provision not allowed
,I/VideoCapabilities( 6530): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,I/art     ( 1472): Explicit concurrent mark sweep GC freed 4111(187KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 680us total 48.870ms
,I/dex2oat ( 6589): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6530): onServiceConnected
W/Babel   ( 6530): Attempted to change video mute state without an active call.
,D/MMApiWebService( 2611): generating token using payload instead of using session token
,D/ Nonce  ( 2611):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2611): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2611): publish the event [tag = MOT_CCE event name = LOG]
,I/Babel   ( 6530): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 6345:com.google.android.deskclock/u0a55 (adj 15): empty #7
,I/dex2oat ( 6589): dex2oat took 178.818ms (threads: 4)
,I/Adreno-EGL( 6513): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6513): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6513): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6513): Local Branch: 
I/Adreno-EGL( 6513): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6513): Local Patches: NONE
I/Adreno-EGL( 6513): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6513): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6513): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6513): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6513): Local Branch: 
I/Adreno-EGL( 6513): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6513): Local Patches: NONE
I/Adreno-EGL( 6513): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  881): failed to open /acct/uid_10055/pid_6345/cgroup.procs: No such file or directory
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6570): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6570): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6570): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6570): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6570): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6570):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6570):   adb logcat -s GAv4
,W/GAv4    ( 6570): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6570): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6570): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6570): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6570): Time to load native libraries: 2 ms (timestamps 8689-8691)
I/LibraryLoader( 6570): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6570): Binding Chromium to main looper Looper (main, tid 1) {11d43d6f}
,I/LibraryLoader( 6570): Expected native library version number "",actual native library version number ""
I/chromium( 6570): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6570): Initializing chromium process, singleProcess=true
W/art     ( 6570): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6570): ApplicationContext is null in ApplicationStatus
,W/chromium( 6570): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6570): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6570): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6570): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6570): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6570): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6570): Local Branch: 
I/Adreno-EGL( 6570): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6570): Local Patches: NONE
I/Adreno-EGL( 6570): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6513): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6513): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6513): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6513): Local Branch: 
I/Adreno-EGL( 6513): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6513): Local Patches: NONE
I/Adreno-EGL( 6513): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6570): Requires BLUETOOTH permission
,I/NSApplication( 6570): Starting up...
,I/Adreno-EGL( 6513): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6513): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6513): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6513): Local Branch: 
I/Adreno-EGL( 6513): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6513): Local Patches: NONE
I/Adreno-EGL( 6513): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6646 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6206): 
I/ActivityManager(  881): Killing 6393:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/WVCdm   (  309): Instantiating CDM.
,I/WVCdm   (  309): CdmEngine::OpenSession
I/WVCdm   (  309): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  309): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  309): Service_Initialize: starts!
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
E/QSEECOMAPI: (  309): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  309): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  309): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  309): App is not loaded in QSEE
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6393/cgroup.procs: No such file or directory
,D/QSEECOMAPI: (  309): Loaded image: APP id = 3
,D/DrmWidevineDash(  309): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffb000
E/DrmWidevineDash(  309): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffb000
,D/DrmWidevineDash(  309): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  309): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  309): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: starts! SID=0xbec9e4e0
D/DrmWidevineDash(  309): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  309): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: starts! randomData=0xb9122948, dataLength=8
D/DrmWidevineDash(  309): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb912ddf8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  309): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  309): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  309): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  309): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  309): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: starts! deviceID=0xb91797b0, idLength=0xb55d6730
,D/DrmWidevineDash(  309): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  309): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  309): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  309): hlos api version =  9
D/DrmWidevineDash(  309): tz api version =  8
D/DrmWidevineDash(  309): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  309): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  309): PrepareKeyRequest: nonce=880781565
D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb90b3770
D/DrmWidevineDash(  309): message_length=1626, signature=0xb912ddf8, signature_length=3042797332
,D/DrmWidevineDash(  309): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  309): CdmEngine::CloseSession
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  309): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  309): L3 Terminate.
D/DrmWidevineDash(  309): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  309): Service_Uninitialize: starts!
D/QSEECOMAPI: (  309): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  309): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  309): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  309): OEMCrypto_Terminate: ends! returns 0
,I/art     (  881): Explicit concurrent mark sweep GC freed 13590(663KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.623ms total 117.641ms
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/ Nonce  ( 2611):  Nonce Reponse 
D/        ( 2611): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"7777e27b-0f85-4a82-a2a1-db3673550260"}
D/MMApiWSBase( 2611): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2611):  Nonce Handle Reponse 
D/MMApiProvisionService( 2611): mOutstandingReq set to false
I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6673 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6438:com.android.mms/u0a23 (adj 15): empty #7
,I/CheckinTask( 1956): Sending checkin request (9533 bytes)
,D/MMApiProvisionService( 2611):  pTime 1455067495665 sExp 172742 cTime 1455113706332 tTime 1455240237665
D/MMApiProvisionService( 2611):  No login Required 
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6438/cgroup.procs: No such file or directory
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  322): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 24.899ms
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6699 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  322): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.469ms
,I/CheckinRequestBuilder( 1956): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1956): Failed to find provider info for com.google.android.wearable.settings
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 29.105ms
,W/DataUsage( 2611): invalid counter update blocked: 'err' by 0
D/Checkin ( 2611): publish the event [tag = MOT_CCE event name = LOG]
I/ActivityManager(  881): Killing 6464:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 6699): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6206): 
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6464/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6732 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6206): 
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6206): 
,I/ActivityManager(  881): Killing 6486:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/MusicStore( 6732): Database version: 120
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6206): 
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6206): 
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6486/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6732): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 1956): Classify the device as Phone.
,I/CheckinTask( 1956): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1956): Checking schedule, now: 1455113707370 next: 1455714844360
I/CheckinService( 1956): active receiver: disabled
,D/CheckinService( 1956): Recording last checkin time for package unspecified as 1455113707386
,I/ActivityManager(  881): Killing 6530:com.google.android.talk/u0a70 (adj 15): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6732): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6732): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6530/cgroup.procs: No such file or directory
,W/ResourcesManager( 6732): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6732): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6732): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6732): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6732): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29e211d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6732): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6732): GMSCore installation verified
,I/ConfigStore( 6732): Config Database version: 1
,I/MediaRouter( 6732): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6732): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6732): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Killing 6570:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,E/libprocessgroup(  881): failed to kill 1 processes for processgroup 6570
,I/NetworkMonitor( 6732): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6777 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6732): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6732): Using platform SSLCertificateSocketFactory
,V/Mms     ( 6777): mnc/mcc: 
V/Mms     ( 6777): tag: int value: recipientLimit - 20
V/Mms     ( 6777): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6777): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6777): tag: int value: maxSubjectLength - 80
V/Mms     ( 6777): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6777): tag: bool value: enableGroupMms - false
I/art     ( 4166): Explicit concurrent mark sweep GC freed 1565(57KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 726us total 31.727ms
,V/Mms     ( 6777):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  881): Killing 6646:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6646/cgroup.procs: No such file or directory
,W/ResourcesManager( 6777): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6816 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6699:android.process.acore/u0a7 (adj 13): empty #7
,D/PhoneMonitor( 6816): Register our PhoneStateListener
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6699/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6816): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6816): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6673:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312220, SEQNUM=4455, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15124, POWER_SUPPLY_CHARGE_COUNTER=-904, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6673/cgroup.procs: No such file or directory
I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1455113707386 min interval config: 0 actual interval: 1883
,D/HeadsetStateMachine( 2489): Disconnected process message: 10, size: 0
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6839 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/HeadsetStateMachine( 2489): Disconnected process message: 10, size: 0
,I/CheckinService( 1956): Checking schedule, now: 1455113709370 next: 1455113737360
I/CheckinService( 1956): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6860 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6732:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6732/cgroup.procs: No such file or directory
,W/ResourcesManager( 6860): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6860): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6860): MmsConfig.loadMmsSettings
I/Babel_SMS( 6860): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6860): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6860): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6860): MmsConfig.loadFromResources
E/Babel_SMS( 6860): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6860): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  881): Explicit concurrent mark sweep GC freed 9498(495KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.720ms total 125.520ms
,W/Settings( 6860): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6860): startup - clean
,I/Babel   ( 6860): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6892 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6860): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6860): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6860): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 6892): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6892):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6892):   adb logcat -s GAv4
,I/vclib   ( 6860): onServiceConnected
,W/Babel   ( 6860): Attempted to change video mute state without an active call.
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6892): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6892): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6892): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6892): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6892): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
I/Babel   ( 6860): connection state changed from UNKNOWN to CONNECTED
,W/ContextImpl( 6892): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6892): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  881): Killing 6777:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6777/cgroup.procs: No such file or directory
,I/WebViewFactory( 6892): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6892): Time to load native libraries: 2 ms (timestamps 4074-4076)
I/LibraryLoader( 6892): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6892): Binding Chromium to main looper Looper (main, tid 1) {11d43d6f}
,I/LibraryLoader( 6892): Expected native library version number "",actual native library version number ""
,I/chromium( 6892): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6892): Initializing chromium process, singleProcess=true
,W/art     ( 6892): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6892): ApplicationContext is null in ApplicationStatus
,W/chromium( 6892): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6892): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6892): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6892): Local Branch: 
I/Adreno-EGL( 6892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6892): Local Patches: NONE
I/Adreno-EGL( 6892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 6892): Starting up...
,W/AudioManagerAndroid( 6892): Requires BLUETOOTH permission
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6957 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6816:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6816/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6976 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6839:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6839/cgroup.procs: No such file or directory
,W/ResourcesManager( 6976): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6996 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6892:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 6996): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  881): failed to kill 1 processes for processgroup 6892
I/ActivityManager(  881): Killing 6860:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6860/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2611): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2611): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2611): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2611): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2611): onServiceConnected()
D/GetNotificationsWS( 2611): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2611): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=7031 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/PushService( 2611): started with background data enabled, making sure notification mechanism is enabled
,W/ResourcesManager( 7031): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7058 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.692ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 21.695ms
,I/ActivityManager(  881): Killing 6513:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 24.918ms
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_6513/cgroup.procs: No such file or directory
,D/WearableService( 1747): callingUid 10016, callindPid: 1747
,E/MDM     ( 1747): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1956): Restart initialization of location
,D/AuthorizationBluetoothService( 1747): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7086 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1747): No location to return for getLastLocation()
,W/FusedLocationProvider( 1747): location=null
,I/MusicStore( 7086): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7086): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7086): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7086): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7086): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7086): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7086): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7086): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7086): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29e211d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7086): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7086): GMSCore installation verified
,I/ConfigStore( 7086): Config Database version: 1
,I/MediaRouter( 7086): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7086): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7086): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 7086): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7116 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1538): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GHttpClientFactory( 7086): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7086): Using platform SSLCertificateSocketFactory
V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@256220f3
,I/ActivityManager(  881): Killing 6957:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7116): mnc/mcc: 
V/Mms     ( 7116): tag: int value: recipientLimit - 20
,V/Mms     ( 7116): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7116): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7116): tag: int value: maxSubjectLength - 80
V/Mms     ( 7116): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7116): tag: bool value: enableGroupMms - false
,V/Mms     ( 7116):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6957/cgroup.procs: No such file or directory
,I/GCoreNlp( 1747): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f518207)
,E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33bcaf34)
E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3af0a15d)
E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@148d3ad2)
,E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@187a37a3)
,I/art     (  881): Explicit concurrent mark sweep GC freed 18313(903KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.785ms total 126.067ms
,W/ResourcesManager( 7116): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7150 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6976:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6976/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7150): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7150): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7150): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6996:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6996/cgroup.procs: No such file or directory
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1455113707386 min interval config: 0 actual interval: 7028
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1455113707386 min interval config: 0 actual interval: 7030
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7175 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1956): Checking schedule, now: 1455113714490 next: 1455113737360
I/CheckinService( 1956): active receiver: disabled
,W/ResourcesManager( 7175): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinService( 1956): Checking schedule, now: 1455113714534 next: 1455113737360
I/CheckinService( 1956): active receiver: disabled
,I/Babel_SMS( 7175): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7175): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7175): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7175): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7175): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7175): MmsConfig.loadFromResources
,E/Babel_SMS( 7175): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7175): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7175): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7175): startup - clean
,I/Babel   ( 7175): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7212 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7175): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7175): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7175): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7175): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7175): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7175): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7175): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7175): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7175): onServiceConnected
,W/Babel   ( 7175): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 7212): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7212):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7212):   adb logcat -s GAv4
W/ContextImpl( 7212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7212): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7212): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7212): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7175): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 7031:com.motorola.context/u0a8 (adj 15): empty #7
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6206): 
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6206): 
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_7031/cgroup.procs: No such file or directory
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6206): 
,I/jxcore-log( 6206): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6206): 
,I/WebViewFactory( 7212): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7212): Time to load native libraries: 2 ms (timestamps 8754-8756)
,I/LibraryLoader( 7212): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7212): Binding Chromium to main looper Looper (main, tid 1) {11d43d6f}
,I/LibraryLoader( 7212): Expected native library version number "",actual native library version number ""
,I/chromium( 7212): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7212): Initializing chromium process, singleProcess=true
,W/art     ( 7212): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7212): ApplicationContext is null in ApplicationStatus
,W/chromium( 7212): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7212): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7212): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7212): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7212): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7212): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7212): Local Branch: 
I/Adreno-EGL( 7212): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7212): Local Patches: NONE
I/Adreno-EGL( 7212): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7212): Requires BLUETOOTH permission
,I/NSApplication( 7212): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7276 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7086:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_7086/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7298 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7116:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_7116/cgroup.procs: No such file or directory
,W/ResourcesManager( 7298): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7322 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7058:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/jxcore-log( 6206): Test app app.js loaded
I/jxcore-log( 6206): 
,I/chromium( 6206): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6206): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f5ed95e added. We now have 1 listener(s)
,I/jxcore-log( 6206): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6206): 
,I/ContactLocale( 7322): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 7150:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7058/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7150/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2611): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/jxcore-log( 6206): --= Surplus to requirements =--
I/jxcore-log( 6206): 
I/jxcore-log( 6206): ****TEST TOOK:  ms ****
I/jxcore-log( 6206): 
I/jxcore-log( 6206): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6206): 
,D/GetNotificationsWS( 2611): bindWebServices(): registering our AIDL callback...
I/SundryService( 2611): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2611): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2611): onServiceConnected()
D/GetNotificationsWS( 2611): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2611): unbindWebServices(): un-registering our AIDL callback...
I/PushService( 2611): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2611): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2611): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2611): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  881): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2611): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2611): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2611): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7364 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2611): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2611): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2611): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2611): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2611): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2611): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2611): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2611): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2611): publish the event [tag = MOT_OTA event name = LOG]
,D/PhoneMonitor( 7364): Register our PhoneStateListener
,I/Keyboard.Facilitator( 1414): onFinishInput()
,W/IInputConnectionWrapper( 6206): showStatusIcon on inactive InputConnection
,V/SetupWizard( 7364): Connected to Gservices successfully,
,I/ActivityManager(  881): Killing 7175:com.google.android.talk/u0a70 (adj 15): empty #7
,I/LaunchCheckinHandler(  881): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,274
W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7175/cgroup.procs: No such file or directory
,D/GCM     ( 1747): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1747): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7386 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/AndroidRuntime( 7361): 
D/AndroidRuntime( 7361): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7361): CheckJNI is OFF
,D/AndroidRuntime( 7361): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10530 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6206:com.test.thalitest/u0a530 (adj 9): stop com.test.thalitest
,I/WindowState(  881): WIN DEATH: Window{2d842615 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  881): Client connection lost with reason: 4
,W/PackageSettings(  881): Skipping PackageSetting{119b92e3 com.example.hello/10440} due to missing metadata
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{3d1f1096 u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  881): Spurious death for ProcessRecord{39795e8a 6206:com.test.thalitest/u0a530}, curProc for 6206: null
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10530 user=0: pkg removed
I/ActivityManager(  881):   Force finishing activity ActivityRecord{3d1f1096 u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{3d1f1096 u0 com.test.thalitest/.MainActivity t6 f}
,I/Keyboard.Facilitator( 1414): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1747): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1414): run()
,I/art     ( 3030): Explicit concurrent mark sweep GC freed 9563(2MB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 7MB/12MB, paused 7.386ms total 66.405ms
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7423 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     ( 1956): Explicit concurrent mark sweep GC freed 25638(1653KB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 14MB/24MB, paused 1.457ms total 106.158ms
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/art     (  322): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 35.425ms
,I/Decoder ( 1414): createOrResetDecoder
,I/art     (  322): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 19.812ms
,I/ActivityManager(  881): Killing 7212:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.513ms
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 4302(273KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 499us total 159.951ms
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  881): Explicit concurrent mark sweep GC freed 21006(1296KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.829ms total 181.024ms
,D/AndroidRuntime( 7361): Shutting down VM
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7212/cgroup.procs: No such file or directory
,I/ConfigService( 1747): onCreate
,I/ActivityManager(  881): Killing 7276:com.android.chrome/u0a52 (adj 15): empty #7
,I/Launcher( 1567): Deferring update until onResume
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7276/cgroup.procs: No such file or directory
D/TaskPersister(  881): removeObsoleteFile: deleting file=6_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=5_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1414): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1414): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1414): run()
I/StatsUtilsManager( 1414): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1414): shouldRecordStats() = Too Soon
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7464 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7482 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7298:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7322:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7298/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7322/cgroup.procs: No such file or directory
,W/ResourcesManager( 7482): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
