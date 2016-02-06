#### Test 58380500fccea7e_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 6511): 
D/AndroidRuntime( 6511): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6511): CheckJNI is OFF
D/AndroidRuntime( 6511): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6530 uid=10511 gids={50511, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6511): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6530): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6530): Time to load native libraries: 11 ms (timestamps 7429-7440)
I/LibraryLoader( 6530): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6530): Binding Chromium to main looper Looper (main, tid 1) {c5329c3}
I/LibraryLoader( 6530): Expected native library version number "",actual native library version number ""
,I/chromium( 6530): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6530): Initializing chromium process, singleProcess=true
,W/art     ( 6530): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6530): ApplicationContext is null in ApplicationStatus
,W/chromium( 6530): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6530): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6530): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6530): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6530): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6530): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6530): Local Branch: 
I/Adreno-EGL( 6530): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6530): Local Patches: NONE
I/Adreno-EGL( 6530): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ecf9730:true
,W/ActivityManager(  885): Activity pause timeout for ActivityRecord{2d280cf5 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6530): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6530): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6530): CordovaWebView is running on device made by: motorola
,W/art     ( 6530): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6530): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6530): Render dirty regions requested: true
,D/Atlas   ( 6530): Validating map...
,W/chromium( 6530): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6530): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6530): Enabling debug mode 0
,I/Keyboard.Facilitator( 1419): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,941
,I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +868ms (total +941ms)
,W/IInputConnectionWrapper( 6530): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6530): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6530): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6530): Cannot call determinedVisibility() - never saw a connection for the pid: 6530
,D/JsMessageQueue( 6530): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6530): JniHelper::setJavaVM(0xb862d310), pthread_self() = -1197750320
,I/chromium( 6530): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6530): Initializing JXcore engine
W/jxcore-log( 6530): JXcore engine is ready
,W/Thread-782( 6578): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10511 path="socket:[9838]" dev="sockfs" ino=9838 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-782( 6578): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10511 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-782( 6578): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10511 path="socket:[8597]" dev="sockfs" ino=8597 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-782( 6578): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10511 path="socket:[29343]" dev="sockfs" ino=29343 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6530): Starting JXcore engine
,W/jxcore-log( 6530): Platform android
W/jxcore-log( 6530): 
W/jxcore-log( 6530): Process ARCH arm
W/jxcore-log( 6530): 
,I/jxcore-log( 6530): JXcore Cordova bridge is ready!
I/jxcore-log( 6530): 
,W/jxcore-log( 6530): JXcore engine is started
,I/jxcore-log( 6530): Toggling radios to true
I/jxcore-log( 6530): 
,D/BluetoothAdapter( 6530): enable(): BT is already enabled..!
,D/WifiService(  885): New client listening to asynchronous messages
,D/WifiService(  885): setWifiEnabled: true pid=6530, uid=10511
E/WifiService(  885): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6530): Radios toggled
I/jxcore-log( 6530): 
I/jxcore-log( 6530): My device name is: motorola-XT1072
I/jxcore-log( 6530): 
,I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  309): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  309):  STA Disconnected !!
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): get_property_value, Enter
I/MDMCTBK (  309): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  309): get_property_value, Exit
I/MDMCTBK (  309): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  309): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  309): set_property_value, Enter
I/MDMCTBK (  309): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  309): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  309): set_property_value, Exit
I/MDMCTBK (  309): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  309): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  309): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  309): set_property_value, Enter
I/MDMCTBK (  309): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
I/MDMCTBK (  309): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  309): set_property_value, Exit
E/MDMCTBK (  309): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  309): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  309): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  885): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  885): InitialState.processMessage what=4
,W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885):  0
,D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  306): Clearing all IP addresses on wlan0
,D/TCMD    (  474): NL - Read 60 bytes from update socket.
,D/TCMD    (  474): NL - ignore NL message, type = 21
D/TCMD    (  474): Listening for incoming client connection request
,V/NativeCrypto( 1744): Read error: ssl=0xb89a9e88: I/O error during system call, Connection timed out
,V/NativeCrypto( 1744): SSL shutdown failed: ssl=0xb89a9e88: I/O error during system call, Broken pipe
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info<unknown ssid>
,D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/WifiMetrics(  885): connected time updated 220671
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6594 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  885): Start Disconnecting Watchdog 1
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  309): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  885): ConnectModeState: Network connection lost 
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CommandListener(  306): Clearing all IP addresses on wlan0
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524292
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524292
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,E/ConnectivityService(  885): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
W/ResourcesManager( 6594): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6620 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  326): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.855ms
,I/ActivityManager(  885): Killing 6142:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.235ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.931ms
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_6142/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1435): wlan0: Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1435): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  309): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  309): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/MDMCTBK (  309): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  309): Event received = Trying to associate with
D/TCMD    (  474): Listening for incoming client connection request
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  885): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  885): [1,454,717,811,272 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1d6474c7 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ResourcesManager( 6620): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 6620): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6620): MmsConfig.loadMmsSettings
I/Babel_SMS( 6620): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6620): MmsConfig.loadFromDatabase
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
,D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/wpa_supplicant( 1435): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  309): Event received = Associated with c0:ff:d4
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1435): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1435): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  309): Event received = WPA: Key negotiation com
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  309): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  309):  STA Connected !!
E/MDMCTBK (  309): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  309): get_freq !!, resp=2412
I/MDMCTBK (  309): get_freq !!, Strip data
I/MDMCTBK (  309): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): get_property_value, Enter
I/MDMCTBK (  309): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  309): get_property_value, Exit
I/MDMCTBK (  309): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  309): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  309): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  309): set_property_value, Enter
I/MDMCTBK (  309): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  309): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  309): set_property_value, Exit
I/MDMCTBK (  309): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  309): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  309): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): get_property_value, Enter
I/MDMCTBK (  309): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  309): get_property_value, Exit
I/MDMCTBK (  309): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195233880
I/MDMCTBK (  309): return from set_get_from_wpa_supplicant
I/MDMCTBK (  309): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  309): set_property_value, Enter
I/MDMCTBK (  309): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  309): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  309): set_property_value, Exit
E/MDMCTBK (  309): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  309): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  309): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  309): , reply_len: 3, ret: 0
E/MDMCTBK (  309): MdmCutbackHndler, resp=OK
E/MDMCTBK (  309): 
D/MDMCTBK (  309): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  885): Network connection established
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  885): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  885): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  306): Setting iface cfg
E/WifiStateMachine(  885): Start Dhcp Watchdog 2
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend false
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1435): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  885): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2615753f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2615753f target=com.android.internal.util.StateMachine$SmHandler }
,E/Babel_SMS( 6620): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6620): MmsConfig.loadFromResources
E/Babel_SMS( 6620): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6620): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6620): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6620): startup - clean
,I/Babel   ( 6620): deleted: false for 0
,E/DHCPCD  ( 6658): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6658): version 5.5.6 starting
E/DHCPCD  ( 6658): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6658): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6658): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/art     ( 6620): Suspending all threads took: 5.286ms
,W/VideoCapabilities( 6620): Unrecognized profile 2130706433 for video/avc
D/DHCPCD  ( 6658): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6658): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6658): wlan0: sending REQUEST (xid 0x9f2326ed), next in 4.40 seconds
,W/AudioCapabilities( 6620): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6620): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6620): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6620): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6620): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6620): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6620): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Killing 6203:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6203/cgroup.procs: No such file or directory
,I/vclib   ( 6620): onServiceConnected
W/Babel   ( 6620): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6658): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6658): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6658): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6658): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6658): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6658): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  474): NL - Read 60 bytes from update socket.
D/TCMD    (  474): NL - ignore NL message, type = 20
D/TCMD    (  474): Listening for incoming client connection request
,D/DHCPCD  ( 6658): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  885): WifiStateMachine DHCP successful
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  885): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  885): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  885): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  885): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885):    accepting network in place of null
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  885): send {24b4c9cc, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  885): done {24b4c9cc, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [4ms]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 06 Feb 2016 00:16:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454717813603], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454717813578]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1538): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1295): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2578): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6726 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1478): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2578): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2578): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2578): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2578): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2578): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2578): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2578): [debug] > CusSM.onRadioDown
,D/CCE     ( 2578): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2578): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2578): Registering with Alarm Manager to restart CCE
,I/MusicStore( 6726): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6726): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6726): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6726): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6726): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6726): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     (  885): Explicit concurrent mark sweep GC freed 47028(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.786ms total 137.378ms
,V/JNIHelp ( 6726): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ActivityThread( 6726): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6726): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22c361cf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6726): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6726): GMSCore installation verified
,I/ConfigStore( 6726): Config Database version: 1
,I/MediaRouter( 6726): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6726): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6726): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6726): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6760 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6726): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6726): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 6240:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6240/cgroup.procs: No such file or directory
,V/Mms     ( 6760): mnc/mcc: 
,V/Mms     ( 6760): tag: int value: recipientLimit - 20
V/Mms     ( 6760): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6760): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6760): tag: int value: maxSubjectLength - 80
V/Mms     ( 6760): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6760): tag: bool value: enableGroupMms - false
V/Mms     ( 6760):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6760): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6795 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6469:com.google.android.deskclock/u0a55 (adj 15): empty #7
,D/PhoneMonitor( 6795): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10055/pid_6469/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6795): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6795): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 6594:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_6594/cgroup.procs: No such file or directory
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1454717633553 min interval config: 0 actual interval: 182132
,I/CheckinService( 1958): Checking schedule, now: 1454717815702 next: 1454717663526
I/CheckinService( 1958): active receiver: enabled
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524295
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524295
,I/CheckinService( 1958): Preparing to send checkin request
I/EventLogService( 1958): Accumulating logs since 1454717630389
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6821 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6843 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6843): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/MultiDex( 6843): VM with version 2.1.0 has multidex support
I/MultiDex( 6843): install
I/MultiDex( 6843): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6864 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 6843): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6843): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6843): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14c8e364: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6843): Installed default security provider GmsCore_OpenSSL
,I/Babel   ( 6620): connection state changed from UNKNOWN to CONNECTED
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2578): now: 296836 ,futureTime: 9223372036854775807
D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2578): now: 296837 ,futureTime: 9223372036854775807
D/PollingManager( 2578): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2578): now: 296837 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2578): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/Tethering(  885): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1478): now: 296845 ,futureTime: 86474345
D/OtaApp  ( 2578): [debug] > PollingManagerService, now: 296845 ,futureTime: 76688972
D/Central_PollingManager( 1478): Polling alarm set to expire at: 86474345 Current Time: 296845
D/OtaApp  ( 2578): [debug] > Polling alarm set to expire at: 76688972 Current Time: 296845
,I/NetworkMonitor( 6726): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2578): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2578): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2578): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2578): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2578): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2578): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2578): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2578): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2578): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2578): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2578): createDeviceIdOrLogin update_device
D/Checkin ( 2578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2578): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2578): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     ( 6843): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6843): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 5331(257KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 533us total 27.842ms
,D/CCE     ( 2578): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2578): createDeviceIdOrLogin update_device
,D/Checkin ( 2578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2578): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2578): set mOutstandingReq to true.
I/ Nonce  ( 2578):  Nonce getNonce 
I/ Nonce  ( 2578):  Nonce Request 
I/ Nonce  ( 2578):  Nonce execute Request 
,D/MMApiWebService( 2578): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2578): isDeviceProvisioned: deviceId = 2072049230914535424
,D/NativeLibraryUtils( 6843): Install completed successfully. count=14 extracted=0
D/CCE     ( 2578): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2578): createDeviceIdOrLogin update_device
D/Checkin ( 2578): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2578): Not proxy app, so login/provision not allowed
,I/art     (  885): Explicit concurrent mark sweep GC freed 11643(523KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.640ms total 118.277ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6864): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/art     ( 2578): Explicit concurrent mark sweep GC freed 12377(729KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.048ms total 84.566ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6864): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/WVCdm   (  312): Instantiating CDM.
I/WVCdm   (  312): CdmEngine::OpenSession
I/WVCdm   (  312): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  312): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/GAv4    ( 6864): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6864):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6864):   adb logcat -s GAv4
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  312): Service_Initialize: starts!
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  312): App is not loaded in QSEE
E/QSEECOMAPI: (  312): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  312): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  312): App is not loaded in QSEE
E/QSEECOMAPI: (  312): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  312): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  312): App is not loaded in QSEE
,W/GAv4    ( 6864): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/MMApiWebService( 2578): generating token using payload instead of using session token
D/QSEECOMAPI: (  312): Loaded image: APP id = 3
,D/DrmWidevineDash(  312): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6f000
E/DrmWidevineDash(  312): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6f000
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6864): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6864): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6864): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
D/DrmWidevineDash(  312): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  312): hlos api version =  9
D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  312): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: starts! SID=0xb554a960
D/DrmWidevineDash(  312): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: starts! randomData=0xb7955718, dataLength=8
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb78f47e8, wrapped_rsa_key_length=1280
D/ Nonce  ( 2578):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  312): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  312): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  312): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  312): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a3a7c0, idLength=0xbee002b0
I/MMApiWSBase( 2578): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2578): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  312): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  312): hlos api version =  9
D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  312): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  312): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  312): PrepareKeyRequest: nonce=4292292958
D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb79eef10
D/DrmWidevineDash(  312): message_length=1591, signature=0xb7973fa0, signature_length=3202351764
,W/GAv4    ( 6864): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  312): CdmEngine::CloseSession
D/DrmWidevineDash(  312): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  312): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  312): L3 Terminate.
D/DrmWidevineDash(  312): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  312): Service_Uninitialize: starts!
D/QSEECOMAPI: (  312): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  312): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  312): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_Terminate: ends! returns 0
,I/WebViewFactory( 6864): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 6914): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/LibraryLoader( 6864): Time to load native libraries: 3 ms (timestamps 7761-7764)
,I/LibraryLoader( 6864): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6864): Binding Chromium to main looper Looper (main, tid 1) {14dded94}
,I/LibraryLoader( 6864): Expected native library version number "",actual native library version number ""
,I/chromium( 6864): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6864): Initializing chromium process, singleProcess=true
,W/art     ( 6864): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6864): ApplicationContext is null in ApplicationStatus
,I/dex2oat ( 6914): dex2oat took 62.414ms (threads: 4)
,W/chromium( 6864): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6864): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6864): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6864): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6864): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6864): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6864): Local Branch: 
I/Adreno-EGL( 6864): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6864): Local Patches: NONE
I/Adreno-EGL( 6864): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6843): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6843): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6843): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6843): Local Branch: 
I/Adreno-EGL( 6843): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6843): Local Patches: NONE
I/Adreno-EGL( 6843): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6864): Requires BLUETOOTH permission
,I/NSApplication( 6864): Starting up...
,I/Adreno-EGL( 6843): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6843): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6843): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6843): Local Branch: 
I/Adreno-EGL( 6843): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6843): Local Patches: NONE
I/Adreno-EGL( 6843): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6939 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6726:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6726/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6958 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6760:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_6760/cgroup.procs: No such file or directory
,W/ResourcesManager( 6958): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6843): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6843): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6843): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6843): Local Branch: 
I/Adreno-EGL( 6843): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6843): Local Patches: NONE
I/Adreno-EGL( 6843): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6530): 
,I/Adreno-EGL( 6843): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6843): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6843): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6843): Local Branch: 
I/Adreno-EGL( 6843): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6843): Local Patches: NONE
I/Adreno-EGL( 6843): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ Nonce  ( 2578):  Nonce Reponse 
D/        ( 2578): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"ce8bc71a-5747-4d8b-ba9c-303bad647b5e"}
D/MMApiWSBase( 2578): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2578):  Nonce Handle Reponse 
D/MMApiProvisionService( 2578): mOutstandingReq set to false
,I/WVCdm   (  312): CdmEngine::OpenSession
I/WVCdm   (  312): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  312): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  312): Service_Initialize: starts!
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  312): App is not loaded in QSEE
E/QSEECOMAPI: (  312): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  312): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  312): App is not loaded in QSEE
E/QSEECOMAPI: (  312): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  312): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  312): App is not loaded in QSEE
,D/MMApiProvisionService( 2578):  pTime 1454701130132 sExp 172742 cTime 1454717818353 tTime 1454873872132
D/MMApiProvisionService( 2578):  No login Required 
,D/QSEECOMAPI: (  312): Loaded image: APP id = 3
,D/DrmWidevineDash(  312): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6f000
E/DrmWidevineDash(  312): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6f000
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  312): hlos api version =  9
D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  312): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: starts! SID=0xb554a960
D/DrmWidevineDash(  312): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: starts! randomData=0xb79740d0, dataLength=8
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb794df10, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  312): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  312): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  312): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  312): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a3a800, idLength=0xb544a730
D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  312): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  312): hlos api version =  9
D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  312): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  312): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  312): PrepareKeyRequest: nonce=2460408338
D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb79eef68
D/DrmWidevineDash(  312): message_length=1626, signature=0xb79f3650, signature_length=3041175316
I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6980 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6821:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 6980): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  312): CdmEngine::CloseSession
D/DrmWidevineDash(  312): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  312): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  312): L3 Terminate.
D/DrmWidevineDash(  312): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  312): Service_Uninitialize: starts!
D/QSEECOMAPI: (  312): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  312): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  312): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/ActivityManager(  885): Killing 6795:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/DataUsage( 2578): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2578): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_6821/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_6795/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7007 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7007): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7007): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 1958): Sending checkin request (9734 bytes)
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7007): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7007): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7007): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7007): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7007): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22c361cf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7007): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7007): GMSCore installation verified
,I/ConfigStore( 7007): Config Database version: 1
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6530): 
,I/MediaRouter( 7007): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7007): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7007): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7007): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7041 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6530): 
,I/art     (  326): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 28.223ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.413ms
,I/GHttpClientFactory( 7007): Using our fixed implementation of GMSCore's GoogleHttpClient
I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.805ms
,I/GoogleURLConnFactory( 7007): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 6620:com.google.android.talk/u0a70 (adj 15): empty #7
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6530): 
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6620/cgroup.procs: No such file or directory
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,V/Mms     ( 7041): mnc/mcc: 
V/Mms     ( 7041): tag: int value: recipientLimit - 20
V/Mms     ( 7041): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7041): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7041): tag: int value: maxSubjectLength - 80
V/Mms     ( 7041): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7041): tag: bool value: enableGroupMms - false
V/Mms     ( 7041):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7041): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7071 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  885): Explicit concurrent mark sweep GC freed 9412(488KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.491ms total 123.634ms
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6530): 
,I/ActivityManager(  885): Killing 6864:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7071): Register our PhoneStateListener
,E/libprocessgroup(  885): failed to kill 1 processes for processgroup 6864
,D/MobileConnectivityChangeReceiver( 7071): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7071): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1454717633553 min interval config: 0 actual interval: 186784
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7097 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6939:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_6939/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/art     ( 6386): Explicit concurrent mark sweep GC freed 1495(66KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 373us total 29.966ms
I/CheckinTask( 1958): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1958): Checking schedule, now: 1454717820732 next: 1455318957719
I/CheckinService( 1958): active receiver: disabled
,I/CheckinService( 1958): Checking schedule, now: 1454717820750 next: 1455318957719
I/CheckinService( 1958): active receiver: disabled
D/CheckinService( 1958): Recording last checkin time for package unspecified as 1454717820752
,I/ActivityManager(  885): Killing 6958:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  885): Killing 6980:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6958/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_6980/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7132 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7007:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7007/cgroup.procs: No such file or directory
,W/ResourcesManager( 7132): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7132): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7132): MmsConfig.loadMmsSettings
I/Babel_SMS( 7132): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7132): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7132): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7132): MmsConfig.loadFromResources
E/Babel_SMS( 7132): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7132): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7132): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7132): startup - clean
,I/Babel   ( 7132): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7168 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7132): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7132): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7132): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7132): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7132): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7132): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7132): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 7168): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7168):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7168):   adb logcat -s GAv4
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7168): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 7132): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7168): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/vclib   ( 7132): onServiceConnected
,W/Babel   ( 7132): Attempted to change video mute state without an active call.
,W/GAv4    ( 7168): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7168): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7168): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7168): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7132): connection state changed from UNKNOWN to CONNECTED
W/GAv4    ( 7168): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  885): Killing 7041:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7041/cgroup.procs: No such file or directory
,I/WebViewFactory( 7168): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7168): Time to load native libraries: 1 ms (timestamps 2998-2999)
,I/LibraryLoader( 7168): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7168): Binding Chromium to main looper Looper (main, tid 1) {14dded94}
,I/LibraryLoader( 7168): Expected native library version number "",actual native library version number ""
,I/chromium( 7168): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7168): Initializing chromium process, singleProcess=true
,W/art     ( 7168): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7168): ApplicationContext is null in ApplicationStatus
,W/chromium( 7168): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7168): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7168): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7168): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7168): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7168): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7168): Local Branch: 
I/Adreno-EGL( 7168): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7168): Local Patches: NONE
I/Adreno-EGL( 7168): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7168): Starting up...
,W/AudioManagerAndroid( 7168): Requires BLUETOOTH permission
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7232 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7071:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7071/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7255 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7097:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7097/cgroup.procs: No such file or directory
,W/ResourcesManager( 7255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7281 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7132:com.google.android.talk/u0a70 (adj 13): empty #7
,I/ActivityManager(  885): Killing 7168:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7132/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7168/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2578): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/HeadsetStateMachine( 2487): Disconnected process message: 10, size: 0
,D/GetNotificationsWS( 2578): bindWebServices(): registering our AIDL callback...
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=282, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310465, SEQNUM=4472, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6410, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/SundryService( 2578): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2578): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2578): onServiceConnected()
,D/GetNotificationsWS( 2578): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2578): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7304 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2578): started with background data enabled, making sure notification mechanism is enabled
,I/ContactLocale( 7281): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/WearableService( 1744): callingUid 10016, callindPid: 1744
,D/LocationInitializer( 1958): Restart initialization of location
,D/AuthorizationBluetoothService( 1744): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1744): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7343 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1744): No location to return for getLastLocation()
,W/FusedLocationProvider( 1744): location=null
,I/MusicStore( 7343): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7343): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7343): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7343): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7343): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7343): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7343): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7343): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7343): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22c361cf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7343): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7343): GMSCore installation verified
,I/ConfigStore( 7343): Config Database version: 1
,I/MediaRouter( 7343): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7343): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7343): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7343): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7374 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7343): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7343): Using platform SSLCertificateSocketFactory
,I/art     (  885): Explicit concurrent mark sweep GC freed 13095(677KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.174ms total 121.391ms
,I/ActivityManager(  885): Killing 6843:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6843/cgroup.procs: No such file or directory
,V/Mms     ( 7374): mnc/mcc: 
V/Mms     ( 7374): tag: int value: recipientLimit - 20
V/Mms     ( 7374): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7374): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7374): tag: int value: maxSubjectLength - 80
V/Mms     ( 7374): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7374): tag: bool value: enableGroupMms - false
V/Mms     ( 7374):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7374): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7400 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  326): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.456ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.599ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.470ms
,I/ActivityManager(  885): Killing 7232:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7400): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7232/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7400): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7400): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 7255:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7255/cgroup.procs: No such file or directory
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1454717820752 min interval config: 0 actual interval: 5288
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1454717820752 min interval config: 0 actual interval: 5304
V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@23d3bc17
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7426 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1958): Checking schedule, now: 1454717826124 next: 1454717850719
I/CheckinService( 1958): active receiver: disabled
,I/GCoreNlp( 1744): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/Launcher( 1575): Deferring update until onResume
,I/CheckinService( 1958): Checking schedule, now: 1454717826255 next: 1454717850719
I/CheckinService( 1958): active receiver: disabled
,W/ResourcesManager( 7426): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7426): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7426): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7426): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7426): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7426): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7426): MmsConfig.loadFromResources
,E/Babel_SMS( 7426): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7426): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7426): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7426): startup - clean
,I/Babel   ( 7426): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7461 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7426): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7426): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7426): Unsupported mime video/mpeg2
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7461): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7461):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7461):   adb logcat -s GAv4
,W/ContextImpl( 7461): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7461): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/VideoCapabilities( 7426): Unsupported profile 4 for video/mp4v-es
,W/GAv4    ( 7461): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/VideoCapabilities( 7426): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7426): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7426): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/VideoCapabilities( 7426): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 7461): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7461): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7461): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/vclib   ( 7426): onServiceConnected
W/Babel   ( 7426): Attempted to change video mute state without an active call.
,W/GAv4    ( 7461): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7426): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 7281:android.process.acore/u0a7 (adj 15): empty #7
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1143fe0)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2855a299)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f57095e)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@399dd13f)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33ad7a0c)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d54cf55)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@35065d6a)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e28425b)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18be2af8)
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2de00bd1)
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7281/cgroup.procs: No such file or directory
,I/WebViewFactory( 7461): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7461): Time to load native libraries: 2 ms (timestamps 7789-7791)
I/LibraryLoader( 7461): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7461): Binding Chromium to main looper Looper (main, tid 1) {14dded94}
,I/LibraryLoader( 7461): Expected native library version number "",actual native library version number ""
I/chromium( 7461): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7461): Initializing chromium process, singleProcess=true
W/art     ( 7461): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7461): ApplicationContext is null in ApplicationStatus
,W/chromium( 7461): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7461): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7461): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7461): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7461): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7461): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7461): Local Branch: 
I/Adreno-EGL( 7461): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7461): Local Patches: NONE
I/Adreno-EGL( 7461): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7461): Requires BLUETOOTH permission
,I/NSApplication( 7461): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7525 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7343:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7343/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7544 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7374:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7374/cgroup.procs: No such file or directory
,W/ResourcesManager( 7544): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7567 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7304:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7567): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7400:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/jxcore-log( 6530): Test app app.js loaded
I/jxcore-log( 6530): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): 	Scan mode: 1
I/chromium( 6530): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6530): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be63a8c added. We now have 1 listener(s)
,I/jxcore-log( 6530): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): TAP version 13
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
I/jxcore-log( 6530): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 6530): 
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7304/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7400/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2578): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2578): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2578): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2578): ServiceHandler.handleMessage: mWaitCount=0
,I/jxcore-log( 6530): ok 1 should be equal
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): ok 2 should be equal
I/jxcore-log( 6530): 
D/GetNotificationsWS( 2578): onServiceConnected()
,D/GetNotificationsWS( 2578): onServiceConnected(): Registered for remote service callbacks...
I/jxcore-log( 6530): ok 3 should be equal
I/jxcore-log( 6530): 
I/jxcore-log( 6530): ok 4 should be equal
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
,I/PushService( 2578): started with background data enabled, making sure notification mechanism is enabled
D/GetNotificationsWS( 2578): unbindWebServices(): un-registering our AIDL callback...
I/jxcore-log( 6530): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 6530): 
,D/OtaApp  ( 2578): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2578): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2578): [debug] > In cancelAnyPendingIntentSetPreviously
I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2578): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2578): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2578): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7603 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2578): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2578): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2578): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2578): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2578): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2578): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2578): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2578): publish the event [tag = MOT_OTA event name = LOG]
,I/jxcore-log( 6530): ok 5 should be equal
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): ok 6 should be equal
I/jxcore-log( 6530): 
I/Keyboard.Facilitator( 1419): onFinishInput()
,I/jxcore-log( 6530): ok 7 should be equal
I/jxcore-log( 6530): 
W/IInputConnectionWrapper( 6530): showStatusIcon on inactive InputConnection
I/jxcore-log( 6530): ok 8 should be equal
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
I/jxcore-log( 6530): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 6530): 
,D/PhoneMonitor( 7603): Register our PhoneStateListener
,V/SetupWizard( 7603): Connected to Gservices successfully
,I/jxcore-log( 6530): ok 9 should throw
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 6530): 
,I/ActivityManager(  885): Killing 7426:com.google.android.talk/u0a70 (adj 15): empty #7
,I/jxcore-log( 6530): ok 10 should throw
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # #parseBeacons no beacons returns null
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): ok 11 should be equal
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): ok 12 should throw
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 6530): 
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,416
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7426/cgroup.procs: No such file or directory
,D/GCM     ( 1744): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7626 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6530): ok 13 should be equal
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 6530): 
,I/ActivityManager(  885): Killing 7461:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/jxcore-log( 6530): ok 14 (unnamed assert)
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): ok 15 should be equal
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): ok 16 (unnamed assert)
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): ok 17 (unnamed assert)
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # setup
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 6530): 
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7461/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7650 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7525:com.android.chrome/u0a52 (adj 15): empty #7
,I/jxcore-log( 6530): ok 18 (unnamed assert)
I/jxcore-log( 6530): 
,I/jxcore-log( 6530): # teardown
I/jxcore-log( 6530): 
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7525/cgroup.procs: No such file or directory
,I/jxcore-log( 6530): --= Surplus to requirements =--
I/jxcore-log( 6530): 
I/jxcore-log( 6530): ****TEST TOOK:  ms ****
I/jxcore-log( 6530): 
I/jxcore-log( 6530): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6530): 
,I/art     (  885): Explicit concurrent mark sweep GC freed 18853(947KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.555ms total 118.675ms
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7682 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/AndroidRuntime( 7675): 
D/AndroidRuntime( 7675): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7675): CheckJNI is OFF
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7704 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7567:android.process.acore/u0a7 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7544:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,D/AndroidRuntime( 7675): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10511 user=-1: uninstall pkg
,I/ActivityManager(  885): Killing 6530:com.test.thalitest/u0a511 (adj 9): stop com.test.thalitest
,W/PackageSettings(  885): Skipping PackageSetting{11036878 com.example.hello/10440} due to missing metadata
,I/WindowState(  885): WIN DEATH: Window{44f2c60 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  885): Client connection lost with reason: 4
,I/ActivityManager(  885):   Force finishing activity ActivityRecord{2d280cf5 u0 com.test.thalitest/.MainActivity t6}
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7544/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7567/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Force stopping com.test.thalitest appid=10511 user=0: pkg removed
,I/ActivityManager(  885):   Force finishing activity ActivityRecord{2d280cf5 u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  885): Duplicate finish request for ActivityRecord{2d280cf5 u0 com.test.thalitest/.MainActivity t6 f}
,W/ResourcesManager( 7704): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 3030): Explicit concurrent mark sweep GC freed 9796(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 7MB/12MB, paused 1.075ms total 34.264ms
,W/ActivityManager(  885): Spurious death for ProcessRecord{167404a8 6530:com.test.thalitest/u0a511}, curProc for 6530: null
,W/GeofencerStateMachine( 1744): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1419): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1419): run()
,I/Decoder ( 1419): createOrResetDecoder
,I/ConfigService( 1744): onCreate
,I/art     ( 1575): Explicit concurrent mark sweep GC freed 4690(294KB) AllocSpace objects, 5(240KB) LOS objects, 24% free, 13MB/17MB, paused 1.375ms total 131.154ms
,I/art     ( 1958): Explicit concurrent mark sweep GC freed 31791(1954KB) AllocSpace objects, 12(192KB) LOS objects, 24% free, 14MB/19MB, paused 1.767ms total 147.989ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): run()
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = contacts
,D/TaskPersister(  885): removeObsoleteFile: deleting file=6_task.xml
D/TaskPersister(  885): removeObsoleteFile: deleting file=5_task.xml
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1419): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1419): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1419): run()
I/StatsUtilsManager( 1419): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1419): shouldRecordStats() = Too Soon
,I/Launcher( 1575): Deferring update until onResume
,I/Babel_SMS( 7704): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7704): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7704): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7704): MmsConfig.loadFromDatabase
,I/art     (  885): Explicit concurrent mark sweep GC freed 13705(941KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 2.083ms total 175.305ms
,E/Babel_SMS( 7704): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7704): MmsConfig.loadFromResources
E/Babel_SMS( 7704): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7704): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7704): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7704): startup - clean
,I/Babel   ( 7704): deleted: false for 0
,D/AndroidRuntime( 7675): Shutting down VM
,I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7770 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  326): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.389ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.408ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.153ms
,W/VideoCapabilities( 7704): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7704): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7704): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7704): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7704): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7704): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7704): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7704): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 7770): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7792 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7603:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7603/cgroup.procs: No such file or directory
,I/vclib   ( 7704): onServiceConnected
,W/Babel   ( 7704): Attempted to change video mute state without an active call.
,W/asset   ( 7792): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7792): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7792): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7792): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7704): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7704): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SQLiteLog( 7770): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 7770): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7770): Process: android.process.acore, PID: 7770
E/AndroidRuntime( 7770): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7770): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 7770): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 7770): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 7770): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 7770): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 7770): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 7770): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1736)
E/AndroidRuntime( 7770): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1494)
E/AndroidRuntime( 7770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7770): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  885): Can't write: system_app_crash
E/DropBoxManagerService(  885): java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  885): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  885): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  885): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  885): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  885): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  885): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  885): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  885): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  885): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  885): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  885): 	... 5 more
,V/JNIHelp ( 7704): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Process ( 7770): Sending signal. PID: 7770 SIG: 9
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
