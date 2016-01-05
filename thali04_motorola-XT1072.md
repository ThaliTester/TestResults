#### Test 5507315224df3aa_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 7154): 
D/AndroidRuntime( 7154): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7154): CheckJNI is OFF
D/AndroidRuntime( 7154): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  878): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7173 uid=10411 gids={50411, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7154): Shutting down VM
V/ActivityManager(  878): Display changed displayId=0
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 7173): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 7173): Time to load native libraries: 3 ms (timestamps 7447-7450)
I/LibraryLoader( 7173): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7173): Binding Chromium to main looper Looper (main, tid 1) {35d8d0d7}
I/LibraryLoader( 7173): Expected native library version number "",actual native library version number ""
I/chromium( 7173): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7173): Initializing chromium process, singleProcess=true
W/art     ( 7173): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7173): ApplicationContext is null in ApplicationStatus
W/chromium( 7173): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7173): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7173): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7173): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7173): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7173): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7173): Local Branch: 
I/Adreno-EGL( 7173): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7173): Local Patches: NONE
I/Adreno-EGL( 7173): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  878): Message: 20
D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@211dbec5:true
W/ActivityManager(  878): Activity pause timeout for ActivityRecord{3f705136 u0 com.test.thalitest/.MainActivity t3}
W/art     ( 7173): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7173): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7173): CordovaWebView is running on device made by: motorola
W/art     ( 7173): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7173): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7173): Render dirty regions requested: true
D/Atlas   ( 7173): Validating map...
W/chromium( 7173): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 7173): Initialized EGL, version 1.4
D/OpenGLRenderer( 7173): Enabling debug mode 0
I/Keyboard.Facilitator( 1412): onFinishInput()
I/LaunchCheckinHandler(  878): Displayed com.test.thalitest/.MainActivity,cp,ca,1051
I/ActivityManager(  878): Displayed com.test.thalitest/.MainActivity: +975ms (total +1s51ms)
W/IInputConnectionWrapper( 7173): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 7173): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 7173): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 7173): Cannot call determinedVisibility() - never saw a connection for the pid: 7173
,D/JsMessageQueue( 7173): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7173): JniHelper::setJavaVM(0xb82f0310), pthread_self() = -1201141800
,D/JX-Cordova( 7173): jxcore cordova android initializing
,W/jxcore-log( 7173): Initializing JXcore engine
W/jxcore-log( 7173): JXcore engine is ready
,W/jxcore-log( 7173): Starting JXcore engine
,W/.test.thalitest( 7173): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10411 path="socket:[9307]" dev="sockfs" ino=9307 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 7173): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10411 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 7173): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10411 path="socket:[9492]" dev="sockfs" ino=9492 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 7173): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10411 path="socket:[29712]" dev="sockfs" ino=29712 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 7173): Platform android
W/jxcore-log( 7173): 
W/jxcore-log( 7173): Process ARCH arm
W/jxcore-log( 7173): 
,I/jxcore-log( 7173): JXcore Cordova bridge is ready!
I/jxcore-log( 7173): 
W/jxcore-log( 7173): JXcore engine is started
,I/chromium( 7173): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7173): Toggling radios to true
I/jxcore-log( 7173): 
,D/BluetoothAdapter( 7173): enable(): BT is already enabled..!
,D/WifiService(  878): New client listening to asynchronous messages
,D/WifiService(  878): setWifiEnabled: true pid=7173, uid=10411
E/WifiService(  878): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 7173): Radios toggled
I/jxcore-log( 7173): 
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 7173): Received device characteristics:
I/jxcore-log( 7173): Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 7173): Bluetooth name: XT1072
I/jxcore-log( 7173): Device name: motorola-XT1072
I/jxcore-log( 7173): 
I/jxcore-log( 7173): Perf Test app loaded loaded
I/jxcore-log( 7173): 
,I/jxcore-log( 7173): check test folder
I/jxcore-log( 7173): 
I/jxcore-log( 7173): found test : ./testFindPeers.js
I/jxcore-log( 7173): 
,D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/Tethering(  878): InitialState.processMessage what=4
,I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  290): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  290):  STA Disconnected !!
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
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
,W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
D/Tethering(  878):  0
,I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  290): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  878): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  290): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  878): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 7173): found test : ./testSendData.js
I/jxcore-log( 7173): 
,D/Tethering(  878): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/TCMD    (  487): NL - Read 60 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 21
D/TCMD    (  487): Listening for incoming client connection request
,V/NativeCrypto( 1743): Read error: ssl=0xb862cf10: I/O error during system call, Connection timed out
,V/NativeCrypto( 1743): SSL shutdown failed: ssl=0xb862cf10: I/O error during system call, Broken pipe
,D/ConnectivityService(  878): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  878): connected time updated 123186
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  878): Start Disconnecting Watchdog 1
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  878): ConnectModeState: Network connection lost 
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7243 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/ConnectivityService(  878): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  878): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Disconnected - quitting
,E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524292
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/CSLegacyTypeTracker(  878): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  878): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  878): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  878): NetworkAgent: NetworkAgent channel lost
I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/chromium( 7173): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ResourcesManager( 7243): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1743): Scheduling Phenotype for one-off execution 13136 seconds from now (1452008774005)
,D/GetConfigurationSnapshotOperation( 1743): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/Babel_SMS( 7243): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7243): MmsConfig.loadMmsSettings
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  290): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1396): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  290): Event received = Trying to associate with
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  878): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1396): DSDS: eapol_sm_notify_config config->sim_num = 1
I/Babel_SMS( 7243): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7243): MmsConfig.loadFromDatabase
D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
E/WifiStateMachine(  878): [1,452,008,774,067 ms] noteScanEnd no scan source
,E/WifiStateMachine(  878): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2c89309b sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/Babel_SMS( 7243): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7243): MmsConfig.loadFromResources
,E/Babel_SMS( 7243): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7243): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/PhenotypeFlagCommitter( 1743): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1743): Using platform SSLCertificateSocketFactory
,W/Settings( 7243): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7243): startup - clean
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
,I/wpa_supplicant( 1396): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  487): NL - Read 80 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 80 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  290): Event received = Associated with c0:ff:d4
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  878): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
,D/Tethering(  878):  0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1396): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
D/Tethering(  878): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  290): Event received = WPA: Key negotiation com
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  290): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  290):  STA Connected !!
E/MDMCTBK (  290): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
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
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  290): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  290): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1214288472
I/MDMCTBK (  290): return from set_get_from_wpa_supplicant
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  290): set_property_value, Enter
D/MDMCTBK (  290): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,E/MDMCTBK (  290): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  290): , reply_len: 3, ret: 0
E/MDMCTBK (  290): MdmCutbackHndler, resp=OK
E/MDMCTBK (  290): 
D/MDMCTBK (  290): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
,I/Babel   ( 7243): deleted: false for 0
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  878): Network connection established
,E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  878): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  878): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  878): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
,E/WifiStateMachine(  878): Start Dhcp Watchdog 2
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/Uploader( 1743): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  878): do suspend false
,E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  878): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1632c9da target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1632c9da target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7243): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7243): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7243): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  878): Killing 6885:com.google.android.calendar/u0a49 (adj 15): empty #7
,E/DHCPCD  ( 7290): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 7290): version 5.5.6 starting
,E/DHCPCD  ( 7290): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 7290): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 7290): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  878): failed to open /acct/uid_10049/pid_6885/cgroup.procs: No such file or directory
,I/vclib   ( 7243): onServiceConnected
W/Babel   ( 7243): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 7290): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 7290): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 7290): wlan0: sending REQUEST (xid 0xf04f9ed0), next in 4.85 seconds
,I/DHCPCD  ( 7290): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,E/global frequency( 2567): no tags to log
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/DHCPCD  ( 7290): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 7290): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 7290): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 7290): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 7290): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  487): NL - Read 60 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 20
D/TCMD    (  487): Listening for incoming client connection request
,D/DHCPCD  ( 7290): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/Uploader( 1743): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/art     (  878): Explicit concurrent mark sweep GC freed 54753(2MB) AllocSpace objects, 3(246KB) LOS objects, 33% free, 20MB/30MB, paused 2.096ms total 149.654ms
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  878): WifiStateMachine DHCP successful
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  878): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  878): Adding iface wlan0 to network 101
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  878): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  878): Adding Route [fe80::/64 -> :: wlan0] to network 101
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  878): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/ConnectivityService(  878): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  878): Setting Dns servers for network 101 to [/192.168.1.1]
,E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  878):    accepting network in place of null
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
E/WifiStateMachine(  878): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiStateMachine(  878): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/CSLegacyTypeTracker(  878): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  878): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 15:46:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452008775227], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452008775210]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Validated
D/ConnectivityService(  878): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1287): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1530): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1530): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 5520(228KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 577us total 42.737ms
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2567): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2567): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2567): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2567): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {538ee00, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  878): done {538ee00, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [32ms]
,I/global frequency( 2567): BcsDSCheckin.events found events 71
D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2567): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 2567): Explicit concurrent mark sweep GC freed 20315(1247KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/19MB, paused 970us total 71.724ms
,I/art     ( 1743): Explicit concurrent mark sweep GC freed 96718(5MB) AllocSpace objects, 15(263KB) LOS objects, 39% free, 15MB/25MB, paused 1.664ms total 121.545ms
,I/MMApiWSBase( 2567): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@223a964)
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e23c7cd)
,E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21aab882)
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@10745b93)
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c23f7d0)
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524295
,D/ConnectivityService(  878): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7347 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/MMApiWSBase( 2567): doRequest(): v1/cs/checkin resp length: 4
D/CCE     ( 2567): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2567): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1466): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/global frequency( 2567): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2567): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2567): [debug] > CusSM.onRadioDown
,D/CheckinProvider(  878): 71 events delete 0 left
,I/MusicStore( 7347): Database version: 120
,I/global frequency( 2567): BcsDSCheckin.events found events 0
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2567): BcsTimer.onReceive checkin completed (0:ERROR_OK)
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7347): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7347): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7347): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7347): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7347): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7347): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7347): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7347): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@134d9723: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7347): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7347): GMSCore installation verified
,I/ConfigStore( 7347): Config Database version: 1
,W/DataUsage( 2567): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  878): Explicit concurrent mark sweep GC freed 22299(1172KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.408ms total 120.426ms
,I/MediaRouter( 7347): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7347): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7347): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7347): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7397 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7347): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7347): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 6964:com.google.android.youtube/u0a101 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10101/pid_6964/cgroup.procs: No such file or directory
,V/Mms     ( 7397): mnc/mcc: 
,V/Mms     ( 7397): tag: int value: recipientLimit - 20
,V/Mms     ( 7397): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7397): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7397): tag: int value: maxSubjectLength - 80
V/Mms     ( 7397): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7397): tag: bool value: enableGroupMms - false
V/Mms     ( 7397):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7432 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7068:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_7068/cgroup.procs: No such file or directory
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): now: 198150 ,futureTime: 9223372036854775807
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1466): now: 198152 ,futureTime: 86474558
D/Central_PollingManager( 1466): Polling alarm set to expire at: 86474558 Current Time: 198152
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2567): now: 198154 ,futureTime: 9223372036854775807
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): now: 198155 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 7347): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2567): [debug] > PollingManagerService, now: 198157 ,futureTime: 1684422
,D/OtaApp  ( 2567): [debug] > Polling alarm set to expire at: 1684422 Current Time: 198158
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/PhoneMonitor( 7432): Register our PhoneStateListener
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2567): Not proxy app, so login/provision not allowed
,D/MobileConnectivityChangeReceiver( 7432): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7432): onReceive CONNECTIVITY_CHANGE networkType=1
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2567): set mOutstandingReq to true.
I/ Nonce  ( 2567):  Nonce getNonce 
I/ Nonce  ( 2567):  Nonce Request 
I/ Nonce  ( 2567):  Nonce execute Request 
D/MMApiWebService( 2567): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/ActivityManager(  878): Killing 7243:com.google.android.talk/u0a70 (adj 15): empty #7
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2567): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2567): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2567): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MMApiWebService( 2567): generating token using payload instead of using session token
,D/ Nonce  ( 2567):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2567): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7243/cgroup.procs: No such file or directory
,V/AlarmManager(  878): send {1bab40bc, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/CheckinService( 6526): Checkin interval check for package: unspecified last checkin: 1452008693865 min interval config: 0 actual interval: 84529
,I/CheckinService( 6526): Disabling old GoogleServicesFramework version
,I/CheckinService( 6526): Checking schedule, now: 1452008778422 next: 1452008723768
I/CheckinService( 6526): active receiver: enabled
,I/iu.SyncManager( 6526): SYNC; picasa accounts
,D/NetworkLogImpl( 6526): Loaded NetworkSpeedPredictor
,I/CheckinService( 6526): Preparing to send checkin request
,I/iu.Environment( 6526): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6526): Accumulating logs since 1452008690662
,I/iu.UploadsManager( 6526): num queued entries: 0
,I/iu.UploadsManager( 6526): num updated entries: 0
,I/iu.SyncManager( 6526): NEXT; no task
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7461 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 7173): BLE is supported
I/jxcore-log( 7173): 
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 23.390ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 19.763ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.067ms
,I/CheckinRequestBuilder( 6526): Checkin reason type: 8 attempt count: 1
,D/WifiService(  878): New client listening to asynchronous messages
,E/ActivityThread( 6526): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  878): Explicit concurrent mark sweep GC freed 9681(446KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.537ms total 115.837ms
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7485 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7485): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7502 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7502): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7502): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7502): VM with version 2.1.0 has multidex support
I/MultiDex( 7502): install
I/MultiDex( 7502): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7502): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel_SMS( 7485): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7485): MmsConfig.loadMmsSettings
I/Babel_SMS( 7485): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7485): MmsConfig.loadFromDatabase
,W/ActivityThread( 7502): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7502): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@143079a8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7502): Installed default security provider GmsCore_OpenSSL
,E/Babel_SMS( 7485): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7485): MmsConfig.loadFromResources
,E/Babel_SMS( 7485): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7485): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 7502): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7502): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Settings( 7485): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7485): startup - clean
,I/Babel   ( 7485): deleted: false for 0
,D/NativeLibraryUtils( 7502): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7537 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb4000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb4000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbee784e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb70ea818, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,W/VideoCapabilities( 7485): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb70e0348, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7217d70, idLength=0xb12c1730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=1783969384
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7152820
D/DrmWidevineDash(  294): message_length=1591, signature=0xb7112db8, signature_length=2972456724
,W/AudioCapabilities( 7485): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7485): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7485): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7485): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7485): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7485): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7485): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7485): onServiceConnected
,W/Babel   ( 7485): Attempted to change video mute state without an active call.
,I/ Nonce  ( 2567):  Nonce Reponse 
D/        ( 2567): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"08673f28-9f68-4b5c-938c-56e941ed3189"}
D/MMApiWSBase( 2567): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2567):  Nonce Handle Reponse 
D/MMApiProvisionService( 2567): mOutstandingReq set to false
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
,I/Babel   ( 7485): connection state changed from UNKNOWN to CONNECTED
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  878): Killing 6864:com.motorola.context/u0a8 (adj 15): empty #7
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 4414(188KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 641us total 37.925ms
,D/MMApiProvisionService( 2567):  pTime 1451923699777 sExp 172742 cTime 1452008779960 tTime 1452096441777
D/MMApiProvisionService( 2567):  No login Required 
,I/dex2oat ( 7563): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_6864/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7537): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7537): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7537): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7537): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7537): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7537):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7537):   adb logcat -s GAv4
,W/GAv4    ( 7537): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 7563): dex2oat took 119.109ms (threads: 4)
,I/Adreno-EGL( 7502): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7502): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7502): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7502): Local Branch: 
I/Adreno-EGL( 7502): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7502): Local Patches: NONE
I/Adreno-EGL( 7502): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 7537): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7537): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 7502): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7502): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7502): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7502): Local Branch: 
I/Adreno-EGL( 7502): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7502): Local Patches: NONE
I/Adreno-EGL( 7502): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     ( 6384): Explicit concurrent mark sweep GC freed 1636(59KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 349us total 24.515ms
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
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,W/DataUsage( 2567): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb4000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb4000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb54ef960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb70e1e78, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb70e0348, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7217db0, idLength=0xb55ef730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=1407075789
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7152820
D/DrmWidevineDash(  294): message_length=1626, signature=0xb7112bb8, signature_length=3042899732
,I/WebViewFactory( 7537): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7537): Time to load native libraries: 1 ms (timestamps 459-460)
I/LibraryLoader( 7537): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7537): Binding Chromium to main looper Looper (main, tid 1) {1b499cd8}
,I/LibraryLoader( 7537): Expected native library version number "",actual native library version number ""
I/chromium( 7537): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7537): Initializing chromium process, singleProcess=true
W/art     ( 7537): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7537): ApplicationContext is null in ApplicationStatus
,W/chromium( 7537): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7537): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7537): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7537): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7537): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7537): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7537): Local Branch: 
I/Adreno-EGL( 7537): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7537): Local Patches: NONE
I/Adreno-EGL( 7537): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 7537): Requires BLUETOOTH permission
I/NSApplication( 7537): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7614 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 7347:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_7347/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7502): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7502): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7502): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7502): Local Branch: 
I/Adreno-EGL( 7502): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7502): Local Patches: NONE
I/Adreno-EGL( 7502): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7644 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7397:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 7502): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7502): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7502): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7502): Local Branch: 
I/Adreno-EGL( 7502): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7502): Local Patches: NONE
I/Adreno-EGL( 7502): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_7397/cgroup.procs: No such file or directory
,W/ResourcesManager( 7644): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6526): Classify the device as Phone.
,I/CheckinTask( 6526): Sending checkin request (9513 bytes)
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7668 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7689 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7461:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 7668): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 7432:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7461/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7432/cgroup.procs: No such file or directory
,I/MusicStore( 7689): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7689): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6526): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 6526): Failed to find provider info for com.google.android.wearable.settings
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7689): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7689): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7689): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7689): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7689): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/CheckinRequestBuilder( 6526): Classify the device as Phone.
,I/CheckinTask( 6526): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6526): Checking schedule, now: 1452008782090 next: 1452609919081
I/CheckinService( 6526): active receiver: disabled
,D/CheckinService( 6526): Recording last checkin time for package unspecified as 1452008782103
,I/ActivityManager(  878): Killing 7485:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ActivityThread( 7689): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7689): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@134d9723: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7689): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7689): GMSCore installation verified
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7485/cgroup.procs: No such file or directory
,I/ConfigStore( 7689): Config Database version: 1
,I/MediaRouter( 7689): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7689): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7689): type=WIFI subType= reason=null isConnected=true
,I/art     (  878): Explicit concurrent mark sweep GC freed 10308(523KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.568ms total 118.597ms
,I/ActivityManager(  878): Killing 7537:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_7537/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7689): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7730 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7689): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7689): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 7614:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7730): mnc/mcc: 
,V/Mms     ( 7730): tag: int value: recipientLimit - 20
V/Mms     ( 7730): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7730): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7730): tag: int value: maxSubjectLength - 80
V/Mms     ( 7730): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7730): tag: bool value: enableGroupMms - false
,V/Mms     ( 7730):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_7614/cgroup.procs: No such file or directory
,W/ResourcesManager( 7730): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7765 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7668:android.process.acore/u0a7 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7668/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7765): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7765): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7765): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 7644:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7644/cgroup.procs: No such file or directory
,I/CheckinService( 6526): Checkin interval check for package: unspecified last checkin: 1452008782103 min interval config: 0 actual interval: 799
,I/CheckinService( 6526): Checking schedule, now: 1452008782911 next: 1452008812081
I/CheckinService( 6526): active receiver: disabled
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7788 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7808 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7689:com.google.android.music:main/u0a80 (adj 13): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 25.572ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.290ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.706ms
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_7689/cgroup.procs: No such file or directory
,W/ResourcesManager( 7808): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7808): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7808): MmsConfig.loadMmsSettings
I/Babel_SMS( 7808): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7808): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7808): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7808): MmsConfig.loadFromResources
E/Babel_SMS( 7808): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7808): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7808): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7808): startup - clean
,I/Babel   ( 7808): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7835 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7808): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7808): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7808): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7808): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7808): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7808): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7808): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7808): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7808): onServiceConnected
W/Babel   ( 7808): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7835): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7835): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7835):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7835):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7835): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7835): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7835): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7835): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7835): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7808): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 7730:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7835): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_7730/cgroup.procs: No such file or directory
,I/WebViewFactory( 7835): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7835): Time to load native libraries: 1 ms (timestamps 4291-4292)
,I/LibraryLoader( 7835): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7835): Binding Chromium to main looper Looper (main, tid 1) {1b499cd8}
,I/LibraryLoader( 7835): Expected native library version number "",actual native library version number ""
,I/chromium( 7835): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7835): Initializing chromium process, singleProcess=true
,W/art     ( 7835): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7835): ApplicationContext is null in ApplicationStatus
,W/chromium( 7835): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7835): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7835): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7835): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7835): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7835): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7835): Local Branch: 
I/Adreno-EGL( 7835): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7835): Local Patches: NONE
I/Adreno-EGL( 7835): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7835): Requires BLUETOOTH permission
,I/NSApplication( 7835): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7911 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7765:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7765/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7930 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7788:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7788/cgroup.procs: No such file or directory
,W/ResourcesManager( 7930): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7950 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7835:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7950): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 7808:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_7835/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7808/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2567): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2567): onServiceConnected()
D/GetNotificationsWS( 2567): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2567): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7974 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2567): started with background data enabled, making sure notification mechanism is enabled
,I/MusicStore( 7974): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7974): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7974): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7974): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7974): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7974): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7974): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7974): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7974): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@134d9723: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7974): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7974): GMSCore installation verified
,I/ConfigStore( 7974): Config Database version: 1
,I/MediaRouter( 7974): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7974): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7974): type=WIFI subType= reason=null isConnected=true
,I/art     (  878): Explicit concurrent mark sweep GC freed 11368(558KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.512ms total 112.648ms
,I/NetworkMonitor( 7974): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8004 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7974): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7974): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 7911:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 8004): mnc/mcc: 
,V/Mms     ( 8004): tag: int value: recipientLimit - 20
V/Mms     ( 8004): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 8004): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8004): tag: int value: maxSubjectLength - 80
V/Mms     ( 8004): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8004): tag: bool value: enableGroupMms - false
,V/Mms     ( 8004):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_7911/cgroup.procs: No such file or directory
,W/ResourcesManager( 8004): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8039 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7930:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7930/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8039): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8039): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8039): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 7950:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7950/cgroup.procs: No such file or directory
,I/CheckinService( 6526): Checkin interval check for package: unspecified last checkin: 1452008782103 min interval config: 0 actual interval: 4181
,I/CheckinService( 6526): Checking schedule, now: 1452008786298 next: 1452008812081
I/CheckinService( 6526): active receiver: disabled
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8062 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8082 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7974:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_7974/cgroup.procs: No such file or directory
,W/ResourcesManager( 8082): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8082): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 8082): MmsConfig.loadMmsSettings
I/Babel_SMS( 8082): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8082): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8082): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8082): MmsConfig.loadFromResources
,E/Babel_SMS( 8082): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8082): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8082): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8082): startup - clean
,I/Babel   ( 8082): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8113 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8082): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8082): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8082): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8082): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8082): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8082): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8082): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8082): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8082): onServiceConnected
W/Babel   ( 8082): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8113): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8113): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8113): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8113):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8113):   adb logcat -s GAv4
,I/Babel   ( 8082): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 8004:com.android.mms/u0a23 (adj 15): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8113): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8113): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_8004/cgroup.procs: No such file or directory
,W/GAv4    ( 8113): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8113): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8113): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8113): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8113): Time to load native libraries: 1 ms (timestamps 7666-7667)
,I/LibraryLoader( 8113): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8113): Binding Chromium to main looper Looper (main, tid 1) {1b499cd8}
,I/LibraryLoader( 8113): Expected native library version number "",actual native library version number ""
I/chromium( 8113): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8113): Initializing chromium process, singleProcess=true
,W/art     ( 8113): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8113): ApplicationContext is null in ApplicationStatus
,W/chromium( 8113): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8113): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8113): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8113): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8113): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8113): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8113): Local Branch: 
I/Adreno-EGL( 8113): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8113): Local Patches: NONE
I/Adreno-EGL( 8113): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8113): Requires BLUETOOTH permission
,I/NSApplication( 8113): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8184 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8039:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 21.901ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.782ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.221ms
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_8039/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8203 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7502:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_7502/cgroup.procs: No such file or directory
,W/ResourcesManager( 8203): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8223 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8082:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  878): Killing 8062:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 8223): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_8082/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_8062/cgroup.procs: No such file or directory
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,D/GetNotificationsWS( 2567): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2567): onServiceConnected()
D/GetNotificationsWS( 2567): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 2567): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2567): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2567): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2567): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  878): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2567): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8258 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/IInputConnectionWrapper( 7173): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1412): onFinishInput()
,I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/AlarmManager(  878): done {1bab40bc, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10363ms]
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1290abb1
,I/GCoreNlp( 1743): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/LaunchCheckinHandler(  878): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,182
,I/Launcher( 1567): Deferring update until onResume
,I/art     (  878): Explicit concurrent mark sweep GC freed 18266(915KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.568ms total 115.988ms
,D/WearableService( 1743): callingUid 10016, callindPid: 1743
,E/MDM     ( 1743): [167] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1743): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6526): Restart initialization of location
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1743): No location to return for getLastLocation()
W/FusedLocationProvider( 1743): location=null
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8293 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8293): Register our PhoneStateListener
,V/SetupWizard( 8293): Connected to Gservices successfully
,I/ActivityManager(  878): Killing 8113:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_8113/cgroup.procs: No such file or directory
,D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8321 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8346 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8363 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8184:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  878): Killing 8203:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_8184/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_8203/cgroup.procs: No such file or directory
,W/ResourcesManager( 8363): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8363): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8363): MmsConfig.loadMmsSettings
I/Babel_SMS( 8363): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8363): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8363): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8363): MmsConfig.loadFromResources
E/Babel_SMS( 8363): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8363): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8363): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8363): startup - clean
,I/Babel   ( 8363): deleted: false for 0
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8396 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8363): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8363): Unsupported mime audio/amr-wb-plus
,W/asset   ( 8396): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8396): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8396): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8396): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 8363): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8363): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8363): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8363): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8363): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6526): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/VideoCapabilities( 8363): Unrecognized profile 2130706433 for video/avc
,I/PackageBroadcastService( 6526): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3ebf4ea9 new=com.google.android.velvet.VelvetApplication@3ebf4ea9
,I/UpdateIcingCorporaServi( 8321): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6526): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8429 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 8363): onServiceConnected
,W/Babel   ( 8363): Attempted to change video mute state without an active call.
,W/ResourcesManager( 8363): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8363): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 8429): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 8363): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 8321): UpdateCorporaTask done [took 201 ms] updated apps [took 201 ms] ,
,I/ActivityManager(  878): Killing 8293:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/System  ( 8363): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8363): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_8293/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8461 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8258:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_8258/cgroup.procs: No such file or directory
,I/art     ( 6384): Explicit concurrent mark sweep GC freed 1834(70KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 342us total 23.077ms
,D/Finsky  ( 8461): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8461): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8461): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8461): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8461): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8461): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8461): Skipping gmscore version check
,D/Finsky  ( 8461): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8461): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  878): Killing 8346:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_8346/cgroup.procs: No such file or directory
,D/TaskPersister(  878): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6526): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6526): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  878): Killing 8396:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_8396/cgroup.procs: No such file or directory
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
,I/ActivityManager(  878): Killing 8321:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_8321/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/CheckinService( 6526): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {3dd25bea, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  878): send {391f9571, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [80ms]
V/AlarmManager(  878): done {3dd25bea, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [80ms]
,V/AlarmManager(  878): done {391f9571, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [87ms]
,I/CheckinService( 6526): Checkin interval check for package: unspecified last checkin: 1452008782103 min interval config: 0 actual interval: 44832
,I/CheckinService( 6526): Checking schedule, now: 1452008826947 next: 1452008812081
I/CheckinService( 6526): active receiver: enabled
,I/CheckinService( 6526): Preparing to send checkin request
I/EventLogService( 6526): Accumulating logs since 1452008778646
,I/CheckinRequestBuilder( 6526): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6526): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  878): Explicit concurrent mark sweep GC freed 15057(731KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.659ms total 113.610ms
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8529 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 359us total 24.930ms
,W/ResourcesManager( 8529): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8529): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 21.680ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.291ms
,I/MultiDex( 8529): VM with version 2.1.0 has multidex support
I/MultiDex( 8529): install
I/MultiDex( 8529): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8529): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8529): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8529): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@143079a8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8529): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1743): callingUid 10016, callindPid: 1743
,E/MDM     ( 1743): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1743): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6526): Restart initialization of location
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1743): No location to return for getLastLocation()
W/FusedLocationProvider( 1743): location=null
I/art     ( 8529): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8529): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8529): Install completed successfully. count=14 extracted=0
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
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb2000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb2000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb12c1960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb70eaa70, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb70e0348, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7217d90, idLength=0xb55ef730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=2208024424
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7152820
D/DrmWidevineDash(  294): message_length=1591, signature=0xb70d1910, signature_length=3042899732
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8567): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8567): dex2oat took 65.999ms (threads: 4)
,I/Adreno-EGL( 8529): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8529): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8529): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8529): Local Branch: 
I/Adreno-EGL( 8529): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8529): Local Patches: NONE
I/Adreno-EGL( 8529): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8529): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8529): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8529): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8529): Local Branch: 
I/Adreno-EGL( 8529): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8529): Local Patches: NONE
I/Adreno-EGL( 8529): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
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
D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb2000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb2000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbee784e0
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb70d1bf0, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb70e0348, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7217db0, idLength=0xb55ef730
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
,D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=686853586
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7152820
D/DrmWidevineDash(  294): message_length=1626, signature=0xb71c65e8, signature_length=3042899732
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8529): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8529): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8529): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8529): Local Branch: 
I/Adreno-EGL( 8529): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8529): Local Patches: NONE
I/Adreno-EGL( 8529): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8529): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8529): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8529): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8529): Local Branch: 
I/Adreno-EGL( 8529): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8529): Local Patches: NONE
I/Adreno-EGL( 8529): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6526): Classify the device as Phone.
,I/CheckinTask( 6526): Sending checkin request (9516 bytes)
,I/CheckinRequestBuilder( 6526): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6526): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6526): Classify the device as Phone.
,I/CheckinTask( 6526): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6526): Checking schedule, now: 1452008829983 next: 1452609966974
I/CheckinService( 6526): active receiver: disabled
,D/CheckinService( 6526): Recording last checkin time for package unspecified as 1452008829994
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8596 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8596): Register our PhoneStateListener
,V/SetupWizard( 8596): Connected to Gservices successfully
,D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Killing 8429:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  878): Killing 8223:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_8429/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_8223/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8618 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3cc01929
,I/GCoreNlp( 1743): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8656 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8675 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8461:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_8461/cgroup.procs: No such file or directory
,W/ResourcesManager( 8363): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8363): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8712 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8596:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8675): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_8596/cgroup.procs: No such file or directory
,W/asset   ( 8712): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8712): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8712): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8712): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6526): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6526): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 8618): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3ebf4ea9 new=com.google.android.velvet.VelvetApplication@3ebf4ea9
,I/Icing   ( 6526): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8740 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8740): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8618): UpdateCorporaTask done [took 134 ms] updated apps [took 134 ms] 
,I/art     (  878): Explicit concurrent mark sweep GC freed 17655(912KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.579ms total 117.131ms
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8765 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8529:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_8529/cgroup.procs: No such file or directory
,D/Finsky  ( 8765): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8765): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8765): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8765): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8765): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8765): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8765): Skipping gmscore version check
,I/ActivityManager(  878): Killing 8656:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_8656/cgroup.procs: No such file or directory
,D/Finsky  ( 8765): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8765): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6526): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6526): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  878): Killing 8712:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_8712/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Killing 8363:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_8363/cgroup.procs: No such file or directory
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311681, SEQNUM=4506, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-896, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1412): run()
I/Keyboard.Facilitator( 1412): flushDynamicLanguageModels()
,I/ConfigService( 1743): onCreate
,I/ConfigService( 1743): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ClearcutLoggerApiImpl( 1743): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 7173): Connected to the server!
I/jxcore-log( 7173): 
,I/chromium( 7173): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-REMOVED 3
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
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311820, SEQNUM=4508, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-1070, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {2864b04, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  878): done {2864b04, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 7173): --- start :testFindPeers.js---
I/jxcore-log( 7173): 
,I/jxcore-log( 7173): testFindPeers created [object Object]
I/jxcore-log( 7173): 
,I/jxcore-log( 7173): serverPort is 8876
I/jxcore-log( 7173): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7173): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7173): bind: Binding a new listener
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7173): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7173): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7173): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7173): start: OK
I/io.jxcore.node.ConnectionHelper( 7173): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7173): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7173): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): start: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7173): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
,D/WifiP2pService(  878): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): start: Starting P2P device discovery...
,D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  878): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7173): start: OK
I/jxcore-log( 7173): StartBroadcasting started ok
I/jxcore-log( 7173): 
I/chromium( 7173): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 7173): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7173): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7173): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-82
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/WifiP2pService(  878): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: 3-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 128
D/WifiP2pService(  878):  grpcapab: 9
D/WifiP2pService(  878):  devcapab: 4
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: 3-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 128
D/WifiP2pService(  878):  grpcapab: 9
D/WifiP2pService(  878):  devcapab: 4
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
,D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pService(  878): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service request
,D/WifiP2pManager( 7173): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): Service request added successfully
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-35
I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  878):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  878):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  878):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  878):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  878):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 4488
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  878):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 4488
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-REMOVED 0 
,D/WifiP2pService(  878): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState discover services
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): Service discovery started successfully
,I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-82
I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  878): InactiveState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: 3-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 128
D/WifiP2pService(  878):  grpcapab: 9
D/WifiP2pService(  878):  devcapab: 4
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: 3-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 128
D/WifiP2pService(  878):  grpcapab: 9
D/WifiP2pService(  878):  devcapab: 4
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -82 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  878):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  878):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  878):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  878):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  290): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  878): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 7173): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 7173): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
I/jxcore-log( 7173): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log( 7173): 
I/jxcore-log( 7173): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 7173): 
I/jxcore-log( 7173): weAreDoneNow
I/jxcore-log( 7173): 
,I/jxcore-log( 7173): done, now sending data to server
I/jxcore-log( 7173): 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  290): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  878): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7173): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 7173): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  290): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  878): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 7173): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 7173): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  290): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7173): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7173): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  290): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  878): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7173): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7173): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  878):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  878):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  878):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  878):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
,D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1396): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  878): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  878):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 4488
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  878):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 4488
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
,D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-REMOVED 2 
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 3 c0
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  290): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  878): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper( 7173): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7173): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 0a
D/MDMCTBK (  290): Event received = P2P-SERV-DISC-REQ 2437 0a
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 7e
D/MDMCTBK (  290): Event received = P2P-SERV-DISC-REQ 2437 7e
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  290): Event received = P2P-SERV-DISC-REQ 2437 92
,I/wpa_supplicant( 1396): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1396): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-54
,D/MDMCTBK (  290): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  290): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  878): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  878):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  878):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  878):  primary type: 10-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 392
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 37
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 5: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): restart: Restarting...
,D/WifiP2pService(  878): InactiveState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState clear service request
,D/TCMD    (  487): NL - Read 56 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,--------- beginning of crash
F/libc    ( 1396): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1396 (wpa_supplicant)
,I/libc    ( 1396): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pService(  878): InactiveState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service request
,D/WifiP2pManager( 7173): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): Service request added successfully
,E/QC-QMI  (  441): qmuxd: RX on fd=27 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  441): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  441): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  441): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  441): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/WifiP2pService(  878): InactiveState{ when=0 what=139310 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139310 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7173): Failed to start the service discovery, got error code: 3
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,E/WifiStateMachine(  878): Connection lost, restart supplicant
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): setState: RESTARTING
,D/WifiP2pService(  878): InactiveState{ when=-2ms what=139268 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  878): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  878): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): handleNetworkDisconnect "NG700" nid=0
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  878): failed to set BSSID: any
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/TCMD    (  487): NL - Read 60 bytes from update socket.
,D/TCMD    (  487): NL - ignore NL message, type = 21
D/TCMD    (  487): Listening for incoming client connection request
,V/NativeCrypto( 1743): Read error: ssl=0xb863eb80: I/O error during system call, Connection timed out
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/Settings( 1743): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiMetrics(  878): connected time updated 433474
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 1743): SSL shutdown failed: ssl=0xb863eb80: I/O error during system call, Broken pipe
,D/ConnectivityService(  878): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  878): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=8858 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  878): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Nat464Xlat(  878): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  878): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Disconnected - quitting
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  878): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  878): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  878): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  878): Unexpected BatchedScanResults :null
E/WifiStateMachine(  878): [1,452,009,085,463 ms] noteScanEnd no scan source
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  878): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  878): discovery change broadcast false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiScanningService(  878): SCAN_AVAILABLE : 1
,D/RttService(  878): SCAN_AVAILABLE : 1
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiScanningService(  878): DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  878): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  878): P2pDisablingState
D/WifiP2pService(  878): P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): p2p socket connection lost
D/WifiP2pService(  878): P2pDisabledState
,D/WifiP2pService(  878): P2pDisabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): stop: Stopping services
,D/WifiP2pService(  878): P2pDisabledState{ when=0 what=139298 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139298 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7173): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7173): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7173): onP2pDeviceListChanged: 0 device(s) discovered
D/WifiP2pService(  878): P2pDisabledState{ when=0 what=139268 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139268 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pDisabledState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): DefaultState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/AndroidRuntime( 7173): Shutting down VM
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  878): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:832)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at android.os.Looper.loop(Looper.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7173): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ResourcesManager( 8858): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8883 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8618:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_8618/cgroup.procs: No such file or directory
,W/ResourcesManager( 8883): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/Tethering(  878): InitialState.processMessage what=4
,D/Tethering(  878): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  0
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
D/Tethering(  878): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
,I/Babel_SMS( 8883): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8883): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8883): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8883): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8883): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8883): MmsConfig.loadFromResources
,E/Babel_SMS( 8883): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8883): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8883): startup - clean
,I/Babel   ( 8883): deleted: false for 0
,D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/TCMD    (  487): NL - Read 444 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 17
D/TCMD    (  487): Listening for incoming client connection request
,D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/TCMD    (  487): NL - Read 444 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 17
D/TCMD    (  487): Listening for incoming client connection request
,W/VideoCapabilities( 8883): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8883): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8883): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8883): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8883): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8883): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8883): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8883): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  878): Killing 8675:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_8675/cgroup.procs: No such file or directory
,I/vclib   ( 8883): onServiceConnected
,W/Babel   ( 8883): Attempted to change video mute state without an active call.
,I/MDMCTBK (  290): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  290): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8922 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1466): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2567): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2567): [debug] > CusSM.onRadioDown
,I/MusicStore( 8922): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8922): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8922): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8922): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8922): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8922): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8922): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8922): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8922): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@134d9723: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8922): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8922): GMSCore installation verified
,I/ConfigStore( 8922): Config Database version: 1
,I/MediaRouter( 8922): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8922): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8963 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 22.250ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 19.555ms
,I/GHttpClientFactory( 8922): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8922): Using platform SSLCertificateSocketFactory
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 28.231ms
,I/ActivityManager(  878): Killing 8740:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,V/Mms     ( 8963): mnc/mcc: 
,V/Mms     ( 8963): tag: int value: recipientLimit - 20
V/Mms     ( 8963): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8963): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8963): tag: int value: maxSubjectLength - 80
V/Mms     ( 8963): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8963): tag: bool value: enableGroupMms - false
V/Mms     ( 8963):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_8740/cgroup.procs: No such file or directory
,W/ResourcesManager( 8963): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8999 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8765:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_8765/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8999): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8999): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8999): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 6526): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager(  878): Killing 8883:com.google.android.talk/u0a70 (adj 15): empty #7
,I/iu.UploadsManager( 6526): num queued entries: 0
,I/iu.UploadsManager( 6526): num updated entries: 0
,I/iu.SyncManager( 6526): NEXT; no task
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_8883/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9018 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9041 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8858:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_8858/cgroup.procs: No such file or directory
,W/ResourcesManager( 9041): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9041): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 9041): MmsConfig.loadMmsSettings
I/Babel_SMS( 9041): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9041): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9041): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 9041): MmsConfig.loadFromResources
,E/Babel_SMS( 9041): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9041): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9041): startup - clean
,I/Babel   ( 9041): deleted: false for 0
,I/art     (  878): Explicit concurrent mark sweep GC freed 30417(1730KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.565ms total 134.855ms
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9072 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 9041): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9041): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 9041): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9041): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9041): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9041): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9041): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9041): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 9041): onServiceConnected
W/Babel   ( 9041): Attempted to change video mute state without an active call.
,I/Babel   ( 9041): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  878): Killing 8922:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/GAv4    ( 9072): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9072):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9072):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9072): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9072): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9072): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9072): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_8922/cgroup.procs: No such file or directory
,W/GAv4    ( 9072): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9072): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9072): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/WifiP2pService(  878): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/WebViewFactory( 9072): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9072): Time to load native libraries: 1 ms (timestamps 681-682)
,I/LibraryLoader( 9072): Expected native library version number "",actual native library version number ""
,D/Tethering(  878): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  0
,D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
,V/WebViewChromiumFactoryProvider( 9072): Binding Chromium to main looper Looper (main, tid 1) {1101444a}
D/Tethering(  878): sendTetherStateChangedBroadcast 1, 0, 0
,I/LibraryLoader( 9072): Expected native library version number "",actual native library version number ""
I/chromium( 9072): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TCMD    (  487): NL - Read 1008 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/Tethering(  878): InitialState.processMessage what=4
,D/Tethering(  878): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  0
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
,I/BrowserStartupController( 9072): Initializing chromium process, singleProcess=true
W/art     ( 9072): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9072): ApplicationContext is null in ApplicationStatus
,D/Tethering(  878): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  487): NL - Read 1008 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/QsoftapCmd(  288): Got softap fwreload command we are passing on
D/SoftapController(  288): Softap fwReload - Ok
,D/CommandListener(  288): Setting iface cfg
D/CommandListener(  288): Trying to bring down wlan0
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  878): setWifiState: enabling
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): Supplicant start successful
D/WifiMonitor(  878): startMonitoring(wlan0) with mConnected = false
,W/chromium( 9072): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9072): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9072): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9072): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9072): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9072): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9072): Local Branch: 
I/Adreno-EGL( 9072): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9072): Local Patches: NONE
I/Adreno-EGL( 9072): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/wpa_supplicant( 9137): Successfully initialized wpa_supplicant
E/wpa_supplicant( 9137): Line 13: unknown global field '-'.
E/wpa_supplicant( 9137): Line 13: Invalid configuration line '-'.
I/wpa_supplicant( 9137): rfkill: Cannot open RFKILL control device
D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,W/AudioManagerAndroid( 9072): Requires BLUETOOTH permission
,I/NSApplication( 9072): Starting up...
,I/libmdmdetect( 9137): ESOC framework not supported
E/Diag_Lib( 9137):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 9137): baseband property is set to [msm]
I/libmdmdetect( 9137): ESOC framework not supported
,E/wpa_supplicant( 9137):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9137): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9137): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9137): card_info[i].error_code: 0x0
,E/wpa_supplicant( 9137): SIM/USIM not ready
E/wpa_supplicant( 9137): Error while reading SIM card status
,E/wpa_supplicant( 9137): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9137): card_info[i].card_state: 0x0
E/wpa_supplicant( 9137): card_info[i].error_code: 0x0
E/wpa_supplicant( 9137): SIM/USIM not ready
I/wpa_supplicant( 9137): eap_proxy: Card not ready
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9151 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 8963:com.android.mms/u0a23 (adj 15): empty #7
,E/wpa_supplicant( 9137): Line 31: unknown global field '�'.
E/wpa_supplicant( 9137): Line 31: Invalid configuration line '�'.
I/wpa_supplicant( 9137): rfkill: Cannot open RFKILL control device
D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_8963/cgroup.procs: No such file or directory
,E/wpa_supplicant( 9137): baseband property is set to [msm]
I/libmdmdetect( 9137): ESOC framework not supported
,E/wpa_supplicant( 9137):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9137): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9137): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9137): card_info[i].error_code: 0x0
E/wpa_supplicant( 9137): SIM/USIM not ready
E/wpa_supplicant( 9137): Error while reading SIM card status
E/wpa_supplicant( 9137): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9137): card_info[i].card_state: 0x0
E/wpa_supplicant( 9137): card_info[i].error_code: 0x0
E/wpa_supplicant( 9137): SIM/USIM not ready
I/wpa_supplicant( 9137): eap_proxy: Card not ready
,I/wpa_supplicant( 9137): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
E/WifiStateMachine(  878): Supplicant connection established
E/WifiStateMachine(  878): setWifiState: enabled
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiConfigStore(  878): Loading config and enabling all networks 
,E/WifiConfigStore(  878):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  878):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  878): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  878): Setting external_sim to 1
W/Settings( 9041): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  878): Setting OUI to DA-A1-19
I/WifiNative-HAL(  878): startHal
E/wifi    (  878): getStaticLongField sWifiHalHandle 0xa2dc589c
D/wifi    (  878): halHandle = 0x0, mVM = 0xb82f0310, mCls = 0x2019d2
I/WifiNative-HAL(  878): Could not start hal
,E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 9137): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  878): do suspend true
,D/WifiP2pService(  878): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  878): SCAN_AVAILABLE : 3
,D/RttService(  878): SCAN_AVAILABLE : 3
D/RttService(  878): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  878): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  878): startHal
D/CommandListener(  288): Setting iface cfg
D/CommandListener(  288): Trying to bring up p2p0
D/WifiMonitor(  878): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  878): P2pEnablingState
D/WifiP2pService(  878): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2p socket connection successful
D/WifiP2pService(  878): P2pEnabledState
D/WifiP2pService(  878): sending p2p connection changed broadcast
E/wifi    (  878): getStaticLongField sWifiHalHandle 0xa49e19cc
D/wifi    (  878): halHandle = 0x0, mVM = 0xb82f0310, mCls = 0x19be
I/WifiNative-HAL(  878): Could not start hal
E/WifiScanningService(  878): could not start HAL
,D/WifiNative-HAL(  878): p2pGetDeviceAddress
,D/WifiNative-HAL(  878): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,D/WifiP2pService(  878): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  878): MCC mode enabled 0
,D/WifiP2pService(  878): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  878): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  878): InactiveState
E/WifiStateMachine(  878): set country code US
,E/WifiStateMachine(  878): set frequency band 2
D/WifiP2pService(  878): InactiveState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): InactiveState{ when=-2ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 9137): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info0x
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9171 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 8999:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_8999/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 9171): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MDMCTBK (  290): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  290): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): wifi_connect_to_supplicant, current pid is = 290
,D/MDMCTBK (  290): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  290): wifi_close_sockets: Exit
,E/MDMCTBK (  290): Attach monitor thread
D/MDMCTBK (  290): wifi_ctrl_recv: Exiting
D/MDMCTBK (  290): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  290): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  290): wifi_close_sockets: Exit
I/MDMCTBK (  290): createWifiMonitorThread: Started the wifi monitor thread -1214266736
D/MDMCTBK (  290): wifi_wait_on_socket: Enter monitor thread
E/MDMCTBK (  290): Error: monitor connection not available
D/MDMCTBK (  290): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  290): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  290): wifi_close_sockets: Exit
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9194 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9018:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/EmailService.MarketingOptInSetter( 2567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager(  878): Killing 9041:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_9018/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_9041/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2567): bindWebServices(): registering our AIDL callback...
I/SundryService( 2567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2567): onServiceConnected()
D/GetNotificationsWS( 2567): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2567): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9219 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 9194): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,I/MusicStore( 9219): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9219): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9219): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9219): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9219): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9219): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9219): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9219): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9219): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@134d9723: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9219): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9219): GMSCore installation verified
,I/ConfigStore( 9219): Config Database version: 1
,I/MediaRouter( 9219): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9219): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledStateupdate channel list
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9250 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9219): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9219): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 9072:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_9072/cgroup.procs: No such file or directory
,V/Mms     ( 9250): mnc/mcc: 
,V/Mms     ( 9250): tag: int value: recipientLimit - 20
,V/Mms     ( 9250): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9250): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9250): tag: int value: maxSubjectLength - 80
,V/Mms     ( 9250): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9250): tag: bool value: enableGroupMms - false
V/Mms     ( 9250):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 9250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9280 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9151:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_9151/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9280): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9280): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9280): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 9171:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_9171/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9299 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 24.760ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.117ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.766ms
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9316 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9194:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_9194/cgroup.procs: No such file or directory
,W/ResourcesManager( 9316): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/wpa_supplicant( 9137): CTRL_IFACE: Detach monitor /data/misc/cutback/wpa_ctrl_290-4\x00 that cannot receive messages
D/TCMD    (  487): NL - Read 56 bytes from update socket.
,D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
,E/WifiStateMachine(  878): [1,452,009,093,070 ms] noteScanEnd no scan source
,E/WifiStateMachine(  878): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2c89309b sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  878): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  878):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  878): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  878): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,I/Babel_SMS( 9316): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9316): MmsConfig.loadMmsSettings
I/Babel_SMS( 9316): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9316): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9316): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9316): MmsConfig.loadFromResources
,E/Babel_SMS( 9316): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9316): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,E/WifiConfigStore(  878): will read network variables netId=0
,E/WifiStateMachine(  878): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  878): will read network variables netId=0
,W/Settings( 9316): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/wpa_supplicant( 9137): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  878): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 9137): DSDS: eapol_sm_notify_config config->sim_num = 1
I/Babel_Crash( 9316): startup - clean
E/WifiConfigStore(  878): setLastSelectedConfiguration -1
,E/wpa_supplicant( 9137): PNO: In assoc process
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel   ( 9316): deleted: false for 0
,D/TCMD    (  487): NL - Read 312 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 88 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
,D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 80 bytes from update socket.
,D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
D/TCMD    (  487): NL - Read 80 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
,D/TCMD    (  487): Listening for incoming client connection request
,D/TCMD    (  487): NL - Read 68 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
I/wpa_supplicant( 9137): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
,D/Tethering(  878): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  0
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
,I/wpa_supplicant( 9137): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 9137): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/TCMD    (  487): NL - Read 1004 bytes from update socket.
D/TCMD    (  487): NL - message type is RTM_NEWLINK
D/TCMD    (  487): Listening for incoming client connection request
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9344 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  878): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  878): Network connection established
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  878): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  878): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  878): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  878): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
E/WifiStateMachine(  878): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
E/WifiStateMachine(  878): Start Dhcp Watchdog 3
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  878): do suspend false
,E/wpa_supplicant( 9137): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  878): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 9137): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  878): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1632c9da target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1632c9da target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 9316): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9316): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9316): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9316): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9316): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/VideoCapabilities( 9316): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 9344): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/VideoCapabilities( 9316): Unrecognized profile 2130706433 for video/avc
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9344): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/VideoCapabilities( 9316): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 9344): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9344):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9344):   adb logcat -s GAv4
,I/vclib   ( 9316): onServiceConnected
,W/Babel   ( 9316): Attempted to change video mute state without an active call.
,I/Babel   ( 9316): connection state changed from UNKNOWN to DISCONNECTED
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9344): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,I/ActivityManager(  878): Killing 9219:com.google.android.music:main/u0a80 (adj 15): empty #7
W/ContextImpl( 9344): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/DHCPCD  ( 9375): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 9375): version 5.5.6 starting
E/DHCPCD  ( 9375): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 9375): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 9375): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_9219/cgroup.procs: No such file or directory
,W/GAv4    ( 9344): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9344): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9344): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DHCPCD  ( 9375): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 9375): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 9375): wlan0: sending REQUEST (xid 0x9749039), next in 4.50 seconds
,I/art     (  878): Explicit concurrent mark sweep GC freed 38618(2002KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.658ms total 132.825ms
,I/WebViewFactory( 9344): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9344): Time to load native libraries: 2 ms (timestamps 4015-4017)
I/LibraryLoader( 9344): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9344): Binding Chromium to main looper Looper (main, tid 1) {1101444a}
,I/LibraryLoader( 9344): Expected native library version number "",actual native library version number ""
,I/chromium( 9344): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9344): Initializing chromium process, singleProcess=true
W/art     ( 9344): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9344): ApplicationContext is null in ApplicationStatus
,W/chromium( 9344): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9344): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9344): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9344): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9344): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9344): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9344): Local Branch: 
I/Adreno-EGL( 9344): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9344): Local Patches: NONE
I/Adreno-EGL( 9344): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9344): Requires BLUETOOTH permission
,I/NSApplication( 9344): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9424 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9250:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_9250/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9443 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9280:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_9280/cgroup.procs: No such file or directory
,W/ResourcesManager( 9443): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9463 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9316:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 9463): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_9316/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=9499 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9344:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/DHCPCD  ( 9375): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 9375): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 9375): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 9375): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 9375): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 9375): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 9375): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  487): NL - Read 60 bytes from update socket.
D/TCMD    (  487): NL - ignore NL message, type = 20
D/TCMD    (  487): Listening for incoming client connection request
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_9344/cgroup.procs: No such file or directory
,W/ResourcesManager( 9499): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Killing 6526:com.google.android.gms/u0a16 (adj 15): empty #7
,D/WifiService(  878): Client connection lost with reason: 4
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_6526/cgroup.procs: No such file or directory
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  878): WifiStateMachine DHCP successful
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  878): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/ConnectivityService(  878): Adding iface wlan0 to network 102
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
E/WifiStateMachine(  878): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  878): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  878): Adding Route [fe80::/64 -> :: wlan0] to network 102
,E/WifiStateMachine(  878): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  878): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
D/ConnectivityService(  878): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
D/ConnectivityService(  878): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  878): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  878):    accepting network in place of null
D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  878): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  878): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 15:51:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452009095400], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452009095363]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Validated
D/ConnectivityService(  878): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  878): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1530): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524295
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  878): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  290): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  290): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  290): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  290): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  290): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
,I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  290): set_property_value, Enter
,I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2567): now: 518298 ,futureTime: 9223372036854775807
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): now: 518299 ,futureTime: 9223372036854775807
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): now: 518299 ,futureTime: 9223372036854775807
D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9564 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1466): now: 518355 ,futureTime: 86474558
,D/OtaApp  ( 2567): [debug] > PollingManagerService, now: 518360 ,futureTime: 1684422
D/OtaApp  ( 2567): [debug] > Polling alarm set to expire at: 1684422 Current Time: 518360
,D/Central_PollingManager( 1466): Polling alarm set to expire at: 86474558 Current Time: 518362
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2567): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2567): set mOutstandingReq to true.
I/ Nonce  ( 2567):  Nonce getNonce 
I/ Nonce  ( 2567):  Nonce Request 
I/ Nonce  ( 2567):  Nonce execute Request 
,D/MMApiWebService( 2567): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2567): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2567): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2567): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2567): generating token using payload instead of using session token
,D/ Nonce  ( 2567):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2567): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,I/MusicStore( 9564): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9564): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9564): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9564): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9564): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9564): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9564): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9564): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9564): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@134d9723: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9564): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9564): GMSCore installation verified
,I/ConfigStore( 9564): Config Database version: 1
,I/MediaRouter( 9564): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9564): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 9564): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 9564): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9615 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9564): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9564): Using platform SSLCertificateSocketFactory
,I/art     (  878): Explicit concurrent mark sweep GC freed 19481(969KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.958ms total 150.520ms
,I/ActivityManager(  878): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=9639 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9424:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 9615): mnc/mcc: 
V/Mms     ( 9615): tag: int value: recipientLimit - 20
V/Mms     ( 9615): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9615): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9615): tag: int value: maxSubjectLength - 80
V/Mms     ( 9615): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9615): tag: bool value: enableGroupMms - false
V/Mms     ( 9615):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_9424/cgroup.procs: No such file or directory
,W/ResourcesManager( 9639): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9639): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 9615): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 9639): VM with version 2.1.0 has multidex support
I/MultiDex( 9639): install
I/MultiDex( 9639): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9664 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9443:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_9443/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9664): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9664): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 9664): onReceive CONNECTIVITY_CHANGE networkType=1
,V/JNIHelp ( 9639): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ Nonce  ( 2567):  Nonce Reponse 
D/        ( 2567): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"6ed36656-e225-4aa5-9d4c-8aa4caf8a829"}
D/MMApiWSBase( 2567): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2567):  Nonce Handle Reponse 
D/MMApiProvisionService( 2567): mOutstandingReq set to false
,W/ActivityThread( 9639): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9639): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1276b6ee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9639): Installed default security provider GmsCore_OpenSSL
,I/art     ( 2567): Explicit concurrent mark sweep GC freed 42183(2MB) AllocSpace objects, 6(119KB) LOS objects, 40% free, 11MB/19MB, paused 1.405ms total 79.075ms
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 6051(274KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 7MB/12MB, paused 6.835ms total 37.597ms
,I/ActivityManager(  878): Killing 9463:android.process.acore/u0a7 (adj 15): empty #7
,D/MMApiProvisionService( 2567):  pTime 1451923699777 sExp 172742 cTime 1452009099705 tTime 1452096441777
D/MMApiProvisionService( 2567):  No login Required 
,D/NativeLibraryUtils( 9639): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_9463/cgroup.procs: No such file or directory
,I/CheckinService( 9639): Checkin interval check for package: unspecified last checkin: 1452008829994 min interval config: 0 actual interval: 269750
,I/CheckinService( 9639): Disabling old GoogleServicesFramework version
,I/CheckinService( 9639): Checking schedule, now: 1452009099767 next: 1452008859974
I/CheckinService( 9639): active receiver: enabled
,I/CheckinService( 9639): Preparing to send checkin request
,I/EventLogService( 9639): Accumulating logs since 1452008826974
,I/iu.SyncManager( 9639): SYNC; picasa accounts
,D/NetworkLogImpl( 9639): Loaded NetworkSpeedPredictor
,I/iu.Environment( 9639): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 9639): num queued entries: 0
,I/iu.UploadsManager( 9639): num updated entries: 0
I/iu.SyncManager( 9639): NEXT; no task
,I/art     ( 9639): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9639): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9712 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/DataUsage( 2567): invalid counter update blocked: 'err' by 0
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 23.170ms
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 21.356ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.084ms
,I/art     ( 6384): Explicit concurrent mark sweep GC freed 1748(62KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 329us total 39.173ms
,W/ResourcesManager( 9712): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 9639): Checkin reason type: 8 attempt count: 1
D/WifiService(  878): New client listening to asynchronous messages
,E/ActivityThread( 9639): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 9712): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9712): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9712): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 9712): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9712): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9712): MmsConfig.loadFromResources
E/Babel_SMS( 9712): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9712): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9712): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9712): startup - clean
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 9712): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9750 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9768 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 9750): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9750): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/VideoCapabilities( 9712): Unrecognized profile 2130706433 for video/avc
,I/MultiDex( 9750): VM with version 2.1.0 has multidex support
I/MultiDex( 9750): install
I/MultiDex( 9750): VM has multidex support, MultiDex support library is disabled.
,W/AudioCapabilities( 9712): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9712): Unsupported mime video/mpeg2
,V/JNIHelp ( 9750): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
I/VideoCapabilities( 9712): Unsupported profile 4 for video/mp4v-es
,W/ContextImpl( 9768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/VideoCapabilities( 9712): Unrecognized profile 2130706433 for video/avc
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/VideoCapabilities( 9712): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9712): Unrecognized profile 2130706433 for video/avc
,W/ContextImpl( 9768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 9768): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9768):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9768):   adb logcat -s GAv4
,W/VideoCapabilities( 9712): Unrecognized profile 2130706433 for video/avc
,W/ActivityThread( 9750): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9750): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@143079a8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9750): Installed default security provider GmsCore_OpenSSL
I/vclib   ( 9712): onServiceConnected
W/Babel   ( 9712): Attempted to change video mute state without an active call.
,W/GAv4    ( 9768): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9768): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9768): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 9750): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9750): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel   ( 9712): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 9499:com.motorola.context/u0a8 (adj 15): empty #7
,D/NativeLibraryUtils( 9750): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_9499/cgroup.procs: No such file or directory
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
,I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb1000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb1000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbee784e0
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb70d1900, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb70e0348, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7217d70, idLength=0xb5049730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=2110607212
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7152820
D/DrmWidevineDash(  294): message_length=1591, signature=0xb71c65e8, signature_length=3036976916
,I/WebViewFactory( 9768): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9768): Time to load native libraries: 1 ms (timestamps 1163-1164)
I/LibraryLoader( 9768): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9768): Binding Chromium to main looper Looper (main, tid 1) {1b499cd8}
,I/LibraryLoader( 9768): Expected native library version number "",actual native library version number ""
,I/chromium( 9768): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9768): Initializing chromium process, singleProcess=true
,W/art     ( 9768): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9768): ApplicationContext is null in ApplicationStatus
,W/chromium( 9768): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9768): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9768): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9768): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9768): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9768): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9768): Local Branch: 
I/Adreno-EGL( 9768): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9768): Local Patches: NONE
I/Adreno-EGL( 9768): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/art     (  878): Explicit concurrent mark sweep GC freed 10849(548KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 4.424ms total 133.511ms
,W/AudioManagerAndroid( 9768): Requires BLUETOOTH permission
,I/NSApplication( 9768): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9833 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9564:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/dex2oat ( 9834): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_9564/cgroup.procs: No such file or directory
,I/dex2oat ( 9834): dex2oat took 67.540ms (threads: 4)
,I/Adreno-EGL( 9750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9750): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9750): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9750): Local Branch: 
I/Adreno-EGL( 9750): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9750): Local Patches: NONE
I/Adreno-EGL( 9750): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9859 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 9615:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 9750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9750): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9750): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9750): Local Branch: 
I/Adreno-EGL( 9750): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9750): Local Patches: NONE
I/Adreno-EGL( 9750): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  294): Service_Initialize: starts!
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
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_9615/cgroup.procs: No such file or directory
,W/ResourcesManager( 9859): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb1000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4eb1000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb5049960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7152c48, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb70e0838, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7217db0, idLength=0xb54ef730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=2944779405
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb71cc4c8
D/DrmWidevineDash(  294): message_length=1626, signature=0xb70d1878, signature_length=3041851156
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9891 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
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
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  878): Killing 9299:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 9891): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 9664:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_9299/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_9664/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2567): bindWebServices(): registering our AIDL callback...
I/SundryService( 2567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2567): onServiceConnected()
D/GetNotificationsWS( 2567): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2567): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2567): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2567): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2567): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2567): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  878): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1743): callingUid 10016, callindPid: 1743
,E/MDM     ( 1743): [176] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/LocationInitializer( 9639): Restart initialization of location
,D/AuthorizationBluetoothService( 1743): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9926 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1743): No location to return for getLastLocation()
W/FusedLocationProvider( 1743): location=null
,I/Adreno-EGL( 9750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9750): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9750): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9750): Local Branch: 
I/Adreno-EGL( 9750): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9750): Local Patches: NONE
I/Adreno-EGL( 9750): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/IcingInternalCorpora( 9639): getNumBytesRead when not calculated.
,I/Adreno-EGL( 9750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9750): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9750): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9750): Local Branch: 
I/Adreno-EGL( 9750): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9750): Local Patches: NONE
I/Adreno-EGL( 9750): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 9639): Classify the device as Phone.
,I/ActivityManager(  878): Killing 9768:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/CheckinTask( 9639): Sending checkin request (9513 bytes)
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_9768/cgroup.procs: No such file or directory
,E/MDM     ( 1743): [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 9639): Restart initialization of location
,D/AuthorizationBluetoothService( 1743): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1743): No location to return for getLastLocation()
,W/FusedLocationProvider( 1743): location=null
,I/CheckinRequestBuilder( 9639): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 9639): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 9639): Classify the device as Phone.
,I/CheckinTask( 9639): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 9639): Checking schedule, now: 1452009103832 next: 1452610240822
I/CheckinService( 9639): active receiver: disabled
,D/CheckinService( 9639): Recording last checkin time for package unspecified as 1452009103842
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9976 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 9976): Register our PhoneStateListener
,V/SetupWizard( 9976): Connected to Gservices successfully
,I/ActivityManager(  878): Killing 9833:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_9833/cgroup.procs: No such file or directory
,D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311473, SEQNUM=4605, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15725, POWER_SUPPLY_CHARGE_COUNTER=-1456, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,I/MDMCTBK (  290): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  290): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  290): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  290): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  290): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  290): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
,I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ActivityManager(  878): Killing 9859:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_9859/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Killing 9891:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_9891/cgroup.procs: No such file or directory
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=10000 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3c86563d
,I/GCoreNlp( 1743): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,I/art     ( 1743): Explicit concurrent mark sweep GC freed 74783(4MB) AllocSpace objects, 35(560KB) LOS objects, 40% free, 14MB/23MB, paused 1.159ms total 88.186ms
,E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fbe2afb)
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e32f718)
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@278cb571)
,E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c97df56)
,E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@253a7bd7)
,I/art     (  878): Explicit concurrent mark sweep GC freed 18888(969KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.725ms total 128.578ms
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10037 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=10057 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 9926:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_9926/cgroup.procs: No such file or directory
,W/ResourcesManager( 9712): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9712): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9712): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 9712): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9712): Installed default security provider GmsCore_OpenSSL
,I/ContactLocale(10057): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10080 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 9976:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.327ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.059ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.073ms
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_9976/cgroup.procs: No such file or directory
,W/asset   (10080): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager(10080): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager(10080): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10080): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 9639): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi(10000): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3ebf4ea9 new=com.google.android.velvet.VelvetApplication@3ebf4ea9
,I/PackageBroadcastService( 9639): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=10105 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager(10105): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi(10000): UpdateCorporaTask done [took 119 ms] updated apps [took 118 ms] 
,I/Icing   ( 9639): Storage manager: low false usage 1.72MB avail 3.11GB capacity 4.85GB
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10138 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 9639): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  878): Killing 9750:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_9750/cgroup.procs: No such file or directory
,I/Icing   ( 9639): Internal init done: storage state 0
,D/Finsky  (10138): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 9639): Post-init done
,I/Icing   ( 9639): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  (10138): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10138): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10138): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (10138): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (10138): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     (10138): Skipping gmscore version check
,D/Finsky  (10138): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (10138): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  878): Killing 10037:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_10037/cgroup.procs: No such file or directory
,I/Icing   ( 9639): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 9639): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 9639): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  878): Killing 10080:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_10080/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Killing 9712:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_9712/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  290): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  290): NetlinkHandler, interfaceAdded
I/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
E/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  290): , Wifi = 0
I/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
,I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  290): set_property_value, Enter
,I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/CheckinService( 9639): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  290): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  290): NetlinkHandler, interfaceAdded
I/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
,E/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  290): , Wifi = 0
,I/MDMCTBK (  290): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=246, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312382, SEQNUM=4613, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1533, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
,I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=240, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312002, SEQNUM=4615, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-1688, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
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
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  878): send {2864b04, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  878): done {2864b04, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {2864b04, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  878): done {2864b04, *walarm*:android.content.syncmanager.SYNC_ALARM} [6ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=237, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312257, SEQNUM=4619, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-1835, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {32cd653d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  878): done {32cd653d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [3ms]
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [45ms]
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
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=235, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311647, SEQNUM=4620, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-67, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  878): send {3b9facf2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  878): cleanup(): cleared. Last call was 490021 ms ago
I/ActivityManager(  878): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=10211 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [166ms]
,I/GAv4    (10211): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    (10211):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    (10211):   adb logcat -s GAv4
,W/GAv4    (10211): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10211): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10211): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  878): done {3b9facf2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [278ms]
,I/ActivityManager(  878): Killing 10000:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_10000/cgroup.procs: No such file or directory
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
,I/UsageStatsService(  878): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=232, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312517, SEQNUM=4627, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-10, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
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
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {3eda8f43, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  878): done {3eda8f43, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [22ms]
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=231, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312482, SEQNUM=4630, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2435): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  878): send {32cd653d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  878): send {2b8799c0, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  878): done {32cd653d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [22ms]
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [47ms]
,V/AlarmManager(  878): done {2b8799c0, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [53ms]
,I/EventLogService( 9639): Aggregate from 1452009100093 (log), 1452008352825 (data)
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
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  878): send {1f839b5, *walarm*:com.motorola.blur.service.blur.pm.alarmintent}
I/PollingManager( 2567): alarm fired!
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/PollingManager( 2567): now: 1684442 ,futureTime: 9223372036854775807
,I/PollingManager( 2567): alarm fired!
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/PollingManager( 2567): now: 1684450 ,futureTime: 9223372036854775807
,I/PollingManager( 2567): alarm fired!
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/PollingManager( 2567): now: 1684462 ,futureTime: 9223372036854775807
,I/OtaApp  ( 2567): [info] > PollingManagerService, alarm fired!
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > PollingManagerService, now: 1684476 ,futureTime: 3314476
D/OtaApp  ( 2567): [debug] > PollingManagerService, wake lock acquired
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [62ms]
,D/OtaApp  ( 2567): [debug] > PollingManagerService, decideWhoNeedsPolling(): polling cUsPollingService
,D/OtaApp  ( 2567): [debug] > Polling alarm set to expire at: 3314476 Current Time: 1684554
,I/Central_PollingManager( 1466): alarm fired!
,D/Central_PollingManager( 1466): now: 1684556 ,futureTime: 86474558
,D/Central_PollingManager( 1466): Polling alarm set to expire at: 86474558 Current Time: 1684556
,V/AlarmManager(  878): done {1f839b5, *walarm*:com.motorola.blur.service.blur.pm.alarmintent} [149ms]
,D/OtaApp  ( 2567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.cUsPollingService.pollingManagerIntent
,I/OtaApp  ( 2567): [info] > CusPollingService interval expired, doing check for upgrade
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > CusSM.onPollingExpiryNotification
,D/OtaApp  ( 2567): [debug] > PollingManagerService, wake lock released
,E/CdsService( 2567): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2567): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2567): [d] > Check Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072
,I/CdsService( 2567): [i] > Starting webservice android service
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2567): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2567): [d] > appending web service request to serviceHandler
,W/ActivityThread( 2567): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CdsService( 2567): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/EBqVruoFtBpz8AsFcDlvO3b98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTMfOC9Ew8x2Ijnj5je9aUoLM2b%2FHah6SzNW2TiM%2F0Shjm05ssUVO%2B1t3jLJ7SahnCS6BeiJOg%2Bj3PwcskTVl6K4OaAilvFtCdaeXLhaYX3P0ZW6Wp0Ck9O2lo5EO%2BMZAfCZcFDoGy4awAiAUrWCiUF3lmcV0p0uxs909vWaRenCh%2FPkZ%2BR2tUwQpvq77r6lVZ3qPzbGUFYcYfwXK6fEzc47knH9oVEMMoX695%2BWpL2OFKe9%2BsNVgKGShuWeYq8nOXAklu0l4m%2B8Z8%2BphIVKB4q9%2BdU58KCL39MdZ7qgqGPaQ%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/IU0HS28Avcwlntkrfz3%2Fw3b98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcks
,D/CdsService( 2567): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/EBqVruoFtBpz8AsFcDlvO3b98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTMfOC9Ew8x2Ijnj5je9aUoLM2b%2FHah6SzNW2TiM%2F0Shjm05ssUVO%2B1t3jLJ7SahnCS6BeiJOg%2Bj3PwcskTVl6K4OaAilvFtCdaeXLhaYX3P0ZW6Wp0Ck9O2lo5EO%2BMZAfCZcFDoGy4awAiAUrWCiUF3lmcV0p0uxs909vWaRenCh%2FPkZ%2BR2tUwQpvq77r6lVZ3qPzbGUFYcYfwXK6fEzc47knH9oVEMMoX695%2BWpL2OFKe9%2BsNVgKGShuWeYq8nOXAklu0l4m%2B8Z8%2BphIVKB4q9%2BdU58KCL39MdZ7qgqGPaQ%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/IU0HS28Avcwl
,I/OtaApp  ( 2567): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update : 200 : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/EBqVruoFtBpz8AsFcDlvO3b98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTMfOC9Ew8x2Ijnj5je9aUoLM2b%2FHah6SzNW2TiM%2F0Shjm05ssUVO%2B1t3jLJ7SahnCS6BeiJOg%2Bj3PwcskTVl6K4OaAilvFtCdaeXLhaYX3P0ZW6Wp0Ck9O2lo5EO%2BMZAfCZcFDoGy4awAiAUrWCiUF3lmcV0p0uxs909vWaRenCh%2FPkZ%2BR2tUwQpvq77r6lVZ3qPzbGUFYcYfwXK6fEzc47knH9oVEMMoX695%2BWpL2OFKe9%2BsNVgKGShuWeYq8nOXAklu0l4m%2B8Z8%2BphIVKB4q9%2BdU58KCL39MdZ7qgqGPaQ%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/IU0HS28Avcwlntkrfz3%2Fw3b98SYvcz3La8G7Q%2FzZ
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > AndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
I/OtaApp  ( 2567): [info] > Next Polling is scheduled at 1439 mins from now
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > PollingManagerService, registerApp(): cUsPollingService
,D/OtaApp  ( 2567): [debug] > PollingManagerService, registerApp(): cUsPollingService already registered.
,D/OtaApp  ( 2567): [debug] > PollingManagerService, modifyApp(): cUsPollingService
,D/OtaApp  ( 2567): [debug] > calculateShortestInterval(): shortest interval is 1630000
,I/OtaApp  ( 2567): [info] > CusSM.handleNewVersion: was notified of a new version : src Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: dest Blur_Version.22.46.12.thea_reteu.reteuall.en.EU: current Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: size 263329787: contentTimeStamp 1445419042000
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2567): [info] > Device is NOT rooted. persist.qe=qe 0/0
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 2567): [error] > UpgradeSource.isUpgradeAcceptable succeeded 
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > prevDestVersion = Blur_Version.22.46.12.thea_reteu.reteuall.en.EU
,W/OtaApp  ( 2567): [warn] > CusSM.handleNewVersion: already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 2567): [error] > CusSM.failNotify: notification failed from repository upgrade for reason already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; additional information: polling initiated upgrade
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1452010265442, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2567): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1452010265456, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
D/OtaApp  ( 2567): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  NotifiedBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EURepository: upgrade; Location: null; AddOnInfo: polling initiated upgradehttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741452010265467true
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; Repository: upgrade; Location: null; AddOnInfo: polling initiated upgrade; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1452010265
,E/CdsService( 2567): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2567): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2567): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,I/CdsService( 2567): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
D/CdsService( 2567): [d] > appending web service request to serviceHandler
,I/OtaApp  ( 2567): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update handle new version returned false
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
D/OtaApp  ( 2567): [debug] > OTAUpgradeSource.handleCheckWSResponse: authoritative response from BOTA ERR_NOTFOUND
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2567): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: server told to :wait
D/CdsService( 2567): [d] > appending web service response to serviceHandler
D/CdsService( 2567): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072 from queue
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,D/CdsService( 2567): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
,D/CdsService( 2567): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
,D/OtaApp  ( 2567): [debug] > Inside handleStateResponse
,D/OtaApp  ( 2567): [debug] > exec delete from status where _id=1
,D/OtaApp  ( 2567): [debug] > stopTimer, cancel()
,D/OtaApp  ( 2567): [debug] > handleStateResponse server told to : continue
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
,D/OtaApp  ( 2567): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  ResultBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EUalready working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OKhttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741452010268045true
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1452010265
,E/CdsService( 2567): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2567): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2567): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,I/CdsService( 2567): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2567): [d] > appending web service request to serviceHandler
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2567): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2567): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2567): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2567): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  878): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: already sending status
D/CdsService( 2567): [d] > appending web service response to serviceHandler
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/CdsService( 2567): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072 from queue
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2567): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
,D/CdsService( 2567): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
,D/OtaApp  ( 2567): [debug] > Inside handleStateResponse
D/OtaApp  ( 2567): [debug] > exec delete from status where _id=2
,D/OtaApp  ( 2567): [debug] > stopTimer, have stoped, do nothing
D/OtaApp  ( 2567): [debug] > handleStateResponse server told to : continue
D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2567): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2567): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2567): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2567): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  878): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2567): [d] > appending web service response to serviceHandler
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/CdsService( 2567): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 from queue
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2567): [d] > No pending web request. shutdown webservice
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2567): [i] > Stopping webservice android service
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
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
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {2e32c3ad, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  878): send {7e03f16, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  878): Prepared write state in 28ms
,I/ProcessStatsService(  878): Prepared write state in 7ms
,V/AlarmManager(  878): done {2e32c3ad, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [68ms]
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [85ms]
,V/AlarmManager(  878): done {7e03f16, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [97ms]
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  878): Pruning old procstats: /data/system/procstats/state-2016-01-04-17-38-38.bin
,D/ChimeraCfgMgr( 9639): Reading stored module config
,D/ChimeraCfgMgr( 9639): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 9639): Loading module APK com.google.android.play.games
,I/art     (  307): Background concurrent mark sweep GC freed 785(33KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 30.306ms total 61.242ms
,I/LaunchCheckinHandler(  878): cleanup(): cleared. Last call was 171752 ms ago
I/ActivityManager(  878): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=10377 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GamesSyncServiceMain( 9639): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 9639): Failed to execute periodic sync, missing client context - aborting
,I/art     (  878): Explicit concurrent mark sweep GC freed 33422(1819KB) AllocSpace objects, 12(290KB) LOS objects, 33% free, 20MB/30MB, paused 1.600ms total 161.577ms
,W/ResourcesManager(10377): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10377): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (10377): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  (10377): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10377): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager(10377): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10377): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/YouTube MDX(10377): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat (10431): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1549010634.jar --oat-fd=18 --oat-location=/data/data/com.google.android.youtube/cache/ads1549010634.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10377): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/dex2oat (10431): dex2oat took 72.748ms (threads: 4)
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10377): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10377): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10377): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc(10377): Found 10016
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10377): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  878): Killing 10057:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_10057/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {36c9bb3d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  878): send {1ebfef0a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  878): done {1ebfef0a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [25ms]
,V/AlarmManager(  878): done {36c9bb3d, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(10503): 
D/AndroidRuntime(10503): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10503): CheckJNI is OFF
D/AndroidRuntime(10503): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10411 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 7173:com.test.thalitest/u0a411 (adj 9): stop com.test.thalitest
I/WindowState(  878): WIN DEATH: Window{34c4e335 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  878): Client connection lost with reason: 4
W/PackageSettings(  878): Skipping PackageSetting{857067c com.example.hello/10406} due to missing metadata
I/ActivityManager(  878):   Force finishing activity ActivityRecord{3f705136 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  878): Spurious death for ProcessRecord{3e4a037b 7173:com.test.thalitest/u0a411}, curProc for 7173: null
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10411 user=0: pkg removed
I/art     ( 2995): Explicit concurrent mark sweep GC freed 12639(2MB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 7MB/12MB, paused 872us total 46.407ms
I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1743): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1412): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1412): run()
I/Decoder ( 1412): createOrResetDecoder
I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=10533 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1567): Explicit concurrent mark sweep GC freed 5362(325KB) AllocSpace objects, 7(353KB) LOS objects, 24% free, 13MB/17MB, paused 504us total 128.375ms
I/art     (  878): Explicit concurrent mark sweep GC freed 14522(990KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.443ms total 149.178ms
I/art     (  878): WaitForGcToComplete blocked for 48.805ms for cause Explicit
I/ConfigService( 1743): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): run()
D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  878): removeObsoleteFile: deleting file=3_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = user
D/VoicemailCleanupService(10533): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1412): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1412): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1412): run()
I/StatsUtilsManager( 1412): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1412): shouldRecordStats() = Too Soon
I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10558 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale(10533): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  878): Explicit concurrent mark sweep GC freed 3607(177KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.298ms total 219.208ms
I/ActivityManager(  878): Killing 10138:com.android.vending/u0a32 (adj 15): empty #7
D/AndroidRuntime(10503): Shutting down VM
W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_10138/cgroup.procs: No such file or directory
W/asset   (10558): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10558): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10558): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10558): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Launcher( 1567): Deferring update until onResume
I/ActivityManager(  878): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10579 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/ContextImpl(10579): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 9639): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 9639): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 9639): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 9639): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 9639): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1743): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1743): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/GMPM-SVC( 9639): App measurement is starting up, version: 8489
I/GMPM-SVC( 9639): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/gH_CompatibleDatabase( 9639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 9639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 9639): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 9639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=10608 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/ChimeraCfgMgr( 9639): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 9639): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 9639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 9639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 9639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  878): Killing 10105:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/gH_CompatibleDatabase( 9639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 9639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 9639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 9639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 9639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 9639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_10105/cgroup.procs: No such file or directory
I/Icing   ( 9639): doRemovePackageData com.test.thalitest
E/SQLiteDatabase( 9639): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 9639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 9639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 9639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 9639): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 9639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 9639): Opening the database failed, dropping and recreating it
W/BaseAppContext( 9639): Using Auth Proxy for data requests.
W/FileUtils( 9639): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 9639): Failed to open Apps corpus file.
E/Icing   ( 9639): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 9639): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
E/SQLiteDatabase( 9639): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 9639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 9639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 9639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 9639): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 9639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 9639): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 9639): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/GMPM-SVC( 9639): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 9639): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 9639): Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
W/GMPM-SVC( 9639): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 9639): Task exception on worker thread: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/SQLiteDatabase( 9639): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 9639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 9639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 9639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.drive.database.m.b(SourceFile:601)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.drive.database.m.a(SourceFile:595)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.drive.database.o.run(SourceFile:616)
E/SQLiteDatabase( 9639): Failed to open database '/data/data/com.google.android.gms/databases/pluscontacts.db'.
E/SQLiteDatabase( 9639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 9639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 9639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 9639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.people.c.f.d(SourceFile:2487)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.people.c.f.b(SourceFile:787)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 9639): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 9639): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 9639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 9639): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 9639): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 9639): Sending signal. PID: 9639 SIG: 9
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
E/lowmemorykiller(  275): Error writing /proc/9639/oom_score_adj; errno=22

```
