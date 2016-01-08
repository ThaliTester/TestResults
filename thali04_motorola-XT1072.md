#### Test 549702613245198_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 6714): 
D/AndroidRuntime( 6714): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6714): CheckJNI is OFF
D/AndroidRuntime( 6714): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6733 uid=10429 gids={50429, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6714): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6733): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6733): Time to load native libraries: 3 ms (timestamps 7687-7690)
I/LibraryLoader( 6733): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6733): Binding Chromium to main looper Looper (main, tid 1) {38ba2bb9}
I/LibraryLoader( 6733): Expected native library version number "",actual native library version number ""
I/chromium( 6733): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6733): Initializing chromium process, singleProcess=true
W/art     ( 6733): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6733): ApplicationContext is null in ApplicationStatus
W/chromium( 6733): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6733): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6733): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6733): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6733): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6733): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6733): Local Branch: 
I/Adreno-EGL( 6733): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6733): Local Patches: NONE
I/Adreno-EGL( 6733): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aab18b2:true
W/ActivityManager(  880): Activity pause timeout for ActivityRecord{be6266f u0 com.test.thalitest/.MainActivity t3}
W/art     ( 6733): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6733): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6733): CordovaWebView is running on device made by: motorola
W/art     ( 6733): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6733): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6733): Render dirty regions requested: true
D/Atlas   ( 6733): Validating map...
W/chromium( 6733): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6733): Initialized EGL, version 1.4
D/OpenGLRenderer( 6733): Enabling debug mode 0
I/Keyboard.Facilitator( 1419): onFinishInput()
I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,948
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +872ms (total +948ms)
W/IInputConnectionWrapper( 6733): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6733): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6733): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6733): Cannot call determinedVisibility() - never saw a connection for the pid: 6733
,D/JsMessageQueue( 6733): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6733): JniHelper::setJavaVM(0xb72e7310), pthread_self() = -1217952592
,D/JX-Cordova( 6733): jxcore cordova android initializing
,W/jxcore-log( 6733): Initializing JXcore engine
W/jxcore-log( 6733): JXcore engine is ready
,W/jxcore-log( 6733): Starting JXcore engine
,W/.test.thalitest( 6733): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10429 path="socket:[7327]" dev="sockfs" ino=7327 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6733): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10429 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6733): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10429 path="socket:[9505]" dev="sockfs" ino=9505 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6733): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10429 path="socket:[27957]" dev="sockfs" ino=27957 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6733): Platform android
W/jxcore-log( 6733): 
W/jxcore-log( 6733): Process ARCH arm
W/jxcore-log( 6733): 
,I/jxcore-log( 6733): JXcore Cordova bridge is ready!
I/jxcore-log( 6733): 
,W/jxcore-log( 6733): JXcore engine is started
,I/chromium( 6733): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6733): Toggling radios to true
I/jxcore-log( 6733): 
,D/BluetoothAdapter( 6733): enable(): BT is already enabled..!
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=6733, uid=10429
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6733): Radios toggled
I/jxcore-log( 6733): 
,I/wpa_supplicant( 1414): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  306):  STA Disconnected !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  306): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1414): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  306): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  880): InitialState.processMessage what=4
,I/wpa_supplicant( 1414): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  306): Event received = CTRL-EVENT-REGDOM-CHANGE
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880):  0
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1414): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  298): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1709): Read error: ssl=0xb7539048: I/O error during system call, Connection timed out
,D/TCMD    (  455): NL - Read 60 bytes from update socket.
D/TCMD    (  455): NL - ignore NL message, type = 21
D/TCMD    (  455): Listening for incoming client connection request
,V/NativeCrypto( 1709): SSL shutdown failed: ssl=0xb7539048: I/O error during system call, Broken pipe
D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6798 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  880): connected time updated 119684
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1414): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1414): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1414): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  298): Clearing all IP addresses on wlan0
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6798): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  880): Explicit concurrent mark sweep GC freed 49782(2MB) AllocSpace objects, 3(231KB) LOS objects, 33% free, 20MB/30MB, paused 1.816ms total 171.151ms
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  306): Event received = WPS-AP-AVAILABLE 
,D/TCMD    (  455): NL - Read 56 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,I/wpa_supplicant( 1414): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  306): Event received = Trying to associate with
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1414): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiStateMachine(  880): [1,452,283,765,675 ms] noteScanEnd no scan source
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3131d45d sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/PhenotypeConfigurator( 1709): Scheduling Phenotype for one-off execution 2454 seconds from now (1452283765749)
,I/Babel_SMS( 6798): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6798): MmsConfig.loadMmsSettings
I/Babel_SMS( 6798): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6798): MmsConfig.loadFromDatabase
,D/GetConfigurationSnapshotOperation( 1709): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/Babel_SMS( 6798): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6798): MmsConfig.loadFromResources
,E/Babel_SMS( 6798): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6798): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  455): NL - Read 312 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 192 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
,D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 80 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 80 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/TCMD    (  455): NL - Read 68 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1414): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  306): Event received = Associated with c0:ff:d4
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1414): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  306): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1414): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306):  STA Connected !!
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
,D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/TCMD    (  455): NL - Read 1004 bytes from update socket.
D/TCMD    (  455): NL - message type is RTM_NEWLINK
D/TCMD    (  455): Listening for incoming client connection request
E/MDMCTBK (  306): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  306): get_freq !!, resp=2412
I/MDMCTBK (  306): get_freq !!, Strip data
I/MDMCTBK (  306): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  306): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
,I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  306): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  306): MdmCutbackHndler, set WIFI TX pwr !!
,I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
I/MDMCTBK (  306): get_property_value, Exit
,I/MDMCTBK (  306): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1215287840
I/MDMCTBK (  306): return from set_get_from_wpa_supplicant
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
D/MDMCTBK (  306): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  306): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  306): , reply_len: 3, ret: 0
E/MDMCTBK (  306): MdmCutbackHndler, resp=OK
E/MDMCTBK (  306): 
D/MDMCTBK (  306): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/PhenotypeFlagCommitter( 1709): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/CommandListener(  298): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 2
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
I/GoogleURLConnFactory( 1709): Using platform SSLCertificateSocketFactory
,E/wpa_supplicant( 1414): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1414): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1df45ad5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1df45ad5 target=com.android.internal.util.StateMachine$SmHandler }
,W/Settings( 6798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6798): startup - clean
,I/Babel   ( 6798): deleted: false for 0
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6849 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/DHCPCD  ( 6855): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6855): version 5.5.6 starting
,E/DHCPCD  ( 6855): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6855): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6855): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,W/ResourcesManager( 6849): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6798): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6798): Unsupported mime audio/amr-wb-plus
D/DHCPCD  ( 6855): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6855): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6855): wlan0: sending REQUEST (xid 0xf7d21695), next in 4.93 seconds
W/VideoCapabilities( 6798): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6798): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  880): Killing 6507:com.google.android.apps.docs/u0a57 (adj 15): empty #7
W/VideoCapabilities( 6798): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6798): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6798): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6798): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_6507/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6545:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6545/cgroup.procs: No such file or directory
,I/vclib   ( 6798): onServiceConnected
,W/Babel   ( 6798): Attempted to change video mute state without an active call.
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth    ( 1709): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cclog
,E/Uploader( 1709): Failed to get auth token: NetworkError
E/Uploader( 1709): java.io.IOException: NetworkError
E/Uploader( 1709): 	at com.google.android.gms.auth.t.a(SourceFile:498)
E/Uploader( 1709): 	at com.google.android.gms.auth.s.a(SourceFile:908)
E/Uploader( 1709): 	at com.google.android.gms.auth.s.e(SourceFile:528)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.f(SourceFile:315)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.b(SourceFile:195)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.a(SourceFile:146)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.a(SourceFile:73)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:761)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:582)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:471)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:386)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:69)
E/Uploader( 1709): 	at com.google.android.gms.gcm.au.run(SourceFile:140)
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/Auth    ( 1709): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cclog
,E/Uploader( 1709): Failed to get auth token: NetworkError
E/Uploader( 1709): java.io.IOException: NetworkError
E/Uploader( 1709): 	at com.google.android.gms.auth.t.a(SourceFile:498)
E/Uploader( 1709): 	at com.google.android.gms.auth.s.a(SourceFile:908)
E/Uploader( 1709): 	at com.google.android.gms.auth.s.e(SourceFile:528)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.f(SourceFile:315)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.b(SourceFile:195)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.a(SourceFile:146)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.a(SourceFile:73)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:761)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:582)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:471)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:386)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:69)
E/Uploader( 1709): 	at com.google.android.gms.gcm.au.run(SourceFile:140)
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/Auth    ( 1709): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cclog
,E/Uploader( 1709): Failed to get auth token: NetworkError
E/Uploader( 1709): java.io.IOException: NetworkError
E/Uploader( 1709): 	at com.google.android.gms.auth.t.a(SourceFile:498)
E/Uploader( 1709): 	at com.google.android.gms.auth.s.a(SourceFile:908)
E/Uploader( 1709): 	at com.google.android.gms.auth.s.e(SourceFile:528)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.f(SourceFile:315)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.b(SourceFile:195)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.a(SourceFile:146)
E/Uploader( 1709): 	at com.google.android.gms.auth.q.a(SourceFile:73)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:761)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:582)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:471)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:386)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
E/Uploader( 1709): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:69)
E/Uploader( 1709): 	at com.google.android.gms.gcm.au.run(SourceFile:140)
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1709): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/DHCPCD  ( 6855): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6855): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6855): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6855): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6855): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6855): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  455): NL - Read 60 bytes from update socket.
D/TCMD    (  455): NL - ignore NL message, type = 20
D/TCMD    (  455): Listening for incoming client connection request
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/DHCPCD  ( 6855): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880):    accepting network in place of null
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 20:09:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452283767894], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452283767869]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1534): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1534): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=100
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2858): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1460): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6945 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/CCE     ( 2858): Registering with Alarm Manager to restart CCE
D/OtaApp  ( 2858): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2858): [debug] > CusSM.onRadioDown
,D/Central_PollingManager( 1460): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CCE     ( 2858): Registering with Alarm Manager to restart CCE
D/CCE     ( 2858): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2858): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2858): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2858): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2858): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1460): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2858): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/MusicStore( 6945): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6945): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6945): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6945): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6945): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6945): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6945): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524295
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ActivityThread( 6945): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6945): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@223fd4a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6945): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6945): GMSCore installation verified
,I/ConfigStore( 6945): Config Database version: 1
,I/MediaRouter( 6945): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/AlarmManager(  880): send {28bba6ff, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/MusicLeanback( 6945): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6945): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6945): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6987 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6945): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6945): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 6354:android.process.acore/u0a7 (adj 15): empty #7
,E/global frequency( 2858): no tags to log
,D/Checkin ( 2858): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/Mms     ( 6987): mnc/mcc: 
V/Mms     ( 6987): tag: int value: recipientLimit - 20
V/Mms     ( 6987): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6987): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6987): tag: int value: maxSubjectLength - 80
V/Mms     ( 6987): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6987): tag: bool value: enableGroupMms - false
V/Mms     ( 6987):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6354/cgroup.procs: No such file or directory
,D/BSUtils ( 2858): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/ResourcesManager( 6987): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BSUtils ( 2858): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7014 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 20.299ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 19.567ms
,I/BSUtils ( 2858): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.523ms
D/BSUtils ( 2858): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  880): Explicit concurrent mark sweep GC freed 36642(1820KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.674ms total 123.351ms
,I/ActivityManager(  880): Killing 6431:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 7014): Register our PhoneStateListener
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 56560(3MB) AllocSpace objects, 36(1241KB) LOS objects, 39% free, 7MB/12MB, paused 1.006ms total 51.692ms
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,D/BSUtils ( 2858): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2858): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6431/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7014): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7014): onReceive CONNECTIVITY_CHANGE networkType=1
,D/BSUtils ( 2858): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  880): Killing 6798:com.google.android.talk/u0a70 (adj 15): empty #7
,D/BSUtils ( 2858): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2858): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6798/cgroup.procs: No such file or directory
,I/BSUtils ( 2858): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2858): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2858): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2858): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2858): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2858): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2858): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/CheckinService( 6600): Checkin interval check for package: unspecified last checkin: 1452283689546 min interval config: 0 actual interval: 80822
,I/CheckinService( 6600): Disabling old GoogleServicesFramework version
,I/CheckinService( 6600): Checking schedule, now: 1452283770400 next: 1452283719528
I/CheckinService( 6600): active receiver: enabled
,I/iu.SyncManager( 6600): SYNC; picasa accounts
,D/NetworkLogImpl( 6600): Loaded NetworkSpeedPredictor
,I/CheckinService( 6600): Preparing to send checkin request
I/iu.Environment( 6600): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6600): Accumulating logs since 1452283685562
,I/iu.UploadsManager( 6600): num queued entries: 0
,I/iu.UploadsManager( 6600): num updated entries: 0
,I/iu.SyncManager( 6600): NEXT; no task
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7042 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6600): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 6600): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2858): now: 197717 ,futureTime: 9223372036854775807
D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2858): now: 197717 ,futureTime: 9223372036854775807
D/Tethering(  880): MasterInitialState.processMessage what=3
D/PollingManager( 2858): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2858): now: 197718 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2858): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1460): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1460): now: 197723 ,futureTime: 86476061
D/Central_PollingManager( 1460): Polling alarm set to expire at: 86476061 Current Time: 197724
,D/OtaApp  ( 2858): [debug] > PollingManagerService, now: 197725 ,futureTime: 72388187
,D/OtaApp  ( 2858): [debug] > Polling alarm set to expire at: 72388187 Current Time: 197726
,D/OtaApp  ( 2858): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
I/NetworkMonitor( 6945): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2858): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2858): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2858): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2858): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2858): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiProvisionService( 2858): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2858): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2858): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2858): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2858): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 4608(198KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 735us total 32.081ms
,D/CCE     ( 2858): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2858): createDeviceIdOrLogin update_device
,D/Checkin ( 2858): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2858): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2858): isDeviceProvisioned: deviceId = 2072049230914535424
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7068 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/CCE     ( 2858): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2858): createDeviceIdOrLogin update_device
,D/Checkin ( 2858): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2858): isDeviceProvisioned: deviceId = 2072049230914535424
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7086 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     ( 2858): Explicit concurrent mark sweep GC freed 23601(1403KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 11MB/19MB, paused 1.108ms total 73.178ms
,D/MMApiProvisionService( 2858): set mOutstandingReq to true.
I/ Nonce  ( 2858):  Nonce getNonce 
I/ Nonce  ( 2858):  Nonce Request 
I/ Nonce  ( 2858):  Nonce execute Request 
,D/MMApiWebService( 2858): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2858): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     (  880): Explicit concurrent mark sweep GC freed 9056(430KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.950ms total 134.598ms
,D/CCE     ( 2858): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2858): createDeviceIdOrLogin update_device
,D/Checkin ( 2858): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2858): Not proxy app, so login/provision not allowed
,W/ResourcesManager( 7068): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7086): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7086): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/MMApiWebService( 2858): generating token using payload instead of using session token
,D/ Nonce  ( 2858):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
I/MMApiWSBase( 2858): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MultiDex( 7086): VM with version 2.1.0 has multidex support
I/MultiDex( 7086): install
I/MultiDex( 7086): VM has multidex support, MultiDex support library is disabled.
,D/Checkin ( 2858): publish the event [tag = MOT_CCE event name = LOG]
,V/JNIHelp ( 7086): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7086): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7086): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ea327c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7086): Installed default security provider GmsCore_OpenSSL
,I/art     ( 7086): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7086): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 7068): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7068): MmsConfig.loadMmsSettings
I/Babel_SMS( 7068): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7068): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7068): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7068): MmsConfig.loadFromResources
,E/Babel_SMS( 7068): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7068): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 7086): Install completed successfully. count=14 extracted=0
,W/Settings( 7068): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7068): startup - clean
,D/WVCdm   (  311): Instantiating CDM.
,I/WVCdm   (  311): CdmEngine::OpenSession
I/WVCdm   (  311): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  311): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  311): Service_Initialize: starts!
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,D/QSEECOMAPI: (  311): Loaded image: APP id = 3
D/DrmWidevineDash(  311): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fac000
E/DrmWidevineDash(  311): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fac000
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: starts!
D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  311): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: starts! SID=0xb557f960
D/DrmWidevineDash(  311): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: starts! randomData=0xb8254148, dataLength=8
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb81db778, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  311): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  311): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  311): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  311): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: starts! deviceID=0xb8338818, idLength=0xb13ba730
,D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: starts! SID=1
I/Babel   ( 7068): deleted: false for 0
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  311): PrepareKeyRequest: nonce=3592077980
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8208e00
D/DrmWidevineDash(  311): message_length=1591, signature=0xb81dad98, signature_length=2973476628
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7119 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  311): CdmEngine::CloseSession
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  311): L3 Terminate.
D/DrmWidevineDash(  311): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  311): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  311): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  311): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  311): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_Terminate: ends! returns 0
,W/VideoCapabilities( 7068): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7068): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7068): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7068): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7068): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7068): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7068): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7068): Unrecognized profile 2130706433 for video/avc
,I/WVCdm   (  311): CdmEngine::OpenSession
I/WVCdm   (  311): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  311): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/vclib   ( 7068): onServiceConnected
,W/Babel   ( 7068): Attempted to change video mute state without an active call.
D/DrmWidevineDash(  311): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  311): Service_Initialize: starts!
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,D/QSEECOMAPI: (  311): Loaded image: APP id = 3
,D/DrmWidevineDash(  311): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f90000
E/DrmWidevineDash(  311): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f90000
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  311): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: starts! SID=0xb547f960
D/DrmWidevineDash(  311): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_GetRandom: starts! randomData=0xb8254670, dataLength=8
,D/DrmWidevineDash(  311): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb830b420, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  311): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  311): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  311): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  311): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: starts! deviceID=0xb8338858, idLength=0xb547f730
,D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  311): PrepareKeyRequest: nonce=1967554242
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8208e00
D/DrmWidevineDash(  311): message_length=1626, signature=0xb8209460, signature_length=3041392404
,I/Babel   ( 7068): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 6849:com.motorola.context/u0a8 (adj 15): empty #7
,I/ Nonce  ( 2858):  Nonce Reponse 
D/        ( 2858): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"631777be-2943-45d9-b7e5-757d8fa38e03"}
D/MMApiWSBase( 2858): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2858):  Nonce Handle Reponse 
D/MMApiProvisionService( 2858): mOutstandingReq set to false
,D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature returns 0
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6849/cgroup.procs: No such file or directory
,D/MMApiProvisionService( 2858):  pTime 1452280438857 sExp 172742 cTime 1452283772356 tTime 1452453180857
D/MMApiProvisionService( 2858):  No login Required 
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7119): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7119):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7119):   adb logcat -s GAv4
,W/GAv4    ( 7119): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7119): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7119): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/WebViewFactory( 7119): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7119): Time to load native libraries: 2 ms (timestamps 9652-9654)
I/LibraryLoader( 7119): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7119): Binding Chromium to main looper Looper (main, tid 1) {20fc3dc3}
I/LibraryLoader( 7119): Expected native library version number "",actual native library version number ""
I/chromium( 7119): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7119): Initializing chromium process, singleProcess=true
W/art     ( 7119): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7119): ApplicationContext is null in ApplicationStatus
,W/chromium( 7119): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7119): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7119): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7119): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7119): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7119): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7119): Local Branch: 
I/Adreno-EGL( 7119): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7119): Local Patches: NONE
I/Adreno-EGL( 7119): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/DataUsage( 2858): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2858): publish the event [tag = MOT_CCE event name = LOG]
,W/AudioManagerAndroid( 7119): Requires BLUETOOTH permission
,I/NSApplication( 7119): Starting up...
,I/WVCdm   (  311): CdmEngine::CloseSession
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  311): L3 Terminate.
D/DrmWidevineDash(  311): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  311): Service_Uninitialize: starts!
D/QSEECOMAPI: (  311): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  311): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  311): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7186 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6945:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6945/cgroup.procs: No such file or directory
,I/dex2oat ( 7204): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7211 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6987:com.android.mms/u0a23 (adj 15): empty #7
,I/dex2oat ( 7204): dex2oat took 98.449ms (threads: 4)
,I/Adreno-EGL( 7086): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7086): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7086): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7086): Local Branch: 
I/Adreno-EGL( 7086): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7086): Local Patches: NONE
I/Adreno-EGL( 7086): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6987/cgroup.procs: No such file or directory
,W/ResourcesManager( 7211): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Adreno-EGL( 7086): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7086): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7086): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7086): Local Branch: 
I/Adreno-EGL( 7086): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7086): Local Patches: NONE
I/Adreno-EGL( 7086): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/AlarmManager(  880): send {1718a04a, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/Adreno-EGL( 7086): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7086): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7086): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7086): Local Branch: 
I/Adreno-EGL( 7086): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7086): Local Patches: NONE
I/Adreno-EGL( 7086): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7086): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7086): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7086): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7086): Local Branch: 
I/Adreno-EGL( 7086): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7086): Local Patches: NONE
I/Adreno-EGL( 7086): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6600): Classify the device as Phone.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7238 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7042:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7238): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7014:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7042/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7014/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2858): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2858): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2858): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2858): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2858): onServiceConnected()
D/GetNotificationsWS( 2858): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2858): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7273 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2858): started with background data enabled, making sure notification mechanism is enabled
,I/MusicStore( 7273): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7273): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7273): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7273): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 6600): Sending checkin request (9599 bytes)
,W/ResourcesManager( 7273): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7273): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7273): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7273): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@223fd4a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7273): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7273): GMSCore installation verified
,I/ConfigStore( 7273): Config Database version: 1
,I/MediaRouter( 7273): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7273): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7273): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7273): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7306 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7273): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7273): Using platform SSLCertificateSocketFactory
,I/art     (  880): Explicit concurrent mark sweep GC freed 10394(507KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.788ms total 114.258ms
,I/ActivityManager(  880): Killing 7068:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7306): mnc/mcc: 
V/Mms     ( 7306): tag: int value: recipientLimit - 20
V/Mms     ( 7306): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7306): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7306): tag: int value: maxSubjectLength - 80
V/Mms     ( 7306): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7306): tag: bool value: enableGroupMms - false
V/Mms     ( 7306):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/CheckinRequestBuilder( 6600): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7068/cgroup.procs: No such file or directory
,E/ActivityThread( 6600): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7306): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7336 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7119:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7336): Register our PhoneStateListener
,E/libprocessgroup(  880): failed to kill 1 processes for processgroup 7119
,D/MobileConnectivityChangeReceiver( 7336): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7336): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6600): Checkin interval check for package: unspecified last checkin: 1452283689546 min interval config: 0 actual interval: 86308
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7361 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 24.577ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 24.090ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.267ms
,I/ActivityManager(  880): Killing 7186:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7186/cgroup.procs: No such file or directory
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 6600): Classify the device as Phone.
,I/CheckinTask( 6600): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6600): Checking schedule, now: 1452283776299 next: 1452884913290
I/CheckinService( 6600): active receiver: disabled
,I/CheckinService( 6600): Checking schedule, now: 1452283776325 next: 1452884913290
I/CheckinService( 6600): active receiver: disabled
,D/CheckinService( 6600): Recording last checkin time for package unspecified as 1452283776329
,I/ActivityManager(  880): Killing 7238:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7211:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7238/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7211/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7397 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7273:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7273/cgroup.procs: No such file or directory
,W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7397): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7397): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7397): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7397): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7397): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7397): MmsConfig.loadFromResources
E/Babel_SMS( 7397): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7397): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/HeadsetStateMachine( 2714): Disconnected process message: 10, size: 0
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310699, SEQNUM=4441, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=7567, POWER_SUPPLY_CHARGE_COUNTER=170, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/Settings( 7397): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7397): startup - clean
,I/Babel   ( 7397): deleted: false for 0
,D/HeadsetStateMachine( 2714): Disconnected process message: 10, size: 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7433 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7397): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7397): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7397): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7397): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7397): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7397): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7397): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7397): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 7433): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7433):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7433):   adb logcat -s GAv4
,I/vclib   ( 7397): onServiceConnected
,W/Babel   ( 7397): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7433): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 7433): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 7433): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7433): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7433): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7397): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7306:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7433): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7433): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 6733): Test app app.js loaded
I/jxcore-log( 6733): 
,I/chromium( 6733): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7306/cgroup.procs: No such file or directory
,I/WebViewFactory( 7433): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7433): Time to load native libraries: 2 ms (timestamps 5086-5088)
I/LibraryLoader( 7433): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7433): Binding Chromium to main looper Looper (main, tid 1) {38990572}
,I/LibraryLoader( 7433): Expected native library version number "",actual native library version number ""
I/chromium( 7433): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7433): Initializing chromium process, singleProcess=true
W/art     ( 7433): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7433): ApplicationContext is null in ApplicationStatus
,W/chromium( 7433): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7433): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7433): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7433): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7433): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7433): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7433): Local Branch: 
I/Adreno-EGL( 7433): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7433): Local Patches: NONE
I/Adreno-EGL( 7433): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7433): Requires BLUETOOTH permission
,I/NSApplication( 7433): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7500 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7336:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7336/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7519 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7361:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7361/cgroup.procs: No such file or directory
,W/ResourcesManager( 7519): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7539 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7433:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 7539): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7397:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7433/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7397/cgroup.procs: No such file or directory
,V/AlarmManager(  880): done {28bba6ff, *walarm*:com.google.android.intent.action.SEND_IDLE} [10214ms]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7562 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7562): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7562): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7562): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7562): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7562): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7562): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7562): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7562): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7562): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@223fd4a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7562): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7562): GMSCore installation verified
,I/ConfigStore( 7562): Config Database version: 1
,I/art     (  880): Explicit concurrent mark sweep GC freed 12962(668KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.882ms total 129.160ms
,I/MediaRouter( 7562): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7562): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7562): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7562): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7591 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7562): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7562): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 7086:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7086/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,V/Mms     ( 7591): mnc/mcc: 
V/Mms     ( 7591): tag: int value: recipientLimit - 20
,V/Mms     ( 7591): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7591): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7591): tag: int value: maxSubjectLength - 80
V/Mms     ( 7591): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7591): tag: bool value: enableGroupMms - false
V/Mms     ( 7591):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7591): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7625 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7500:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7500/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7625): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7625): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7625): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6600): Checkin interval check for package: unspecified last checkin: 1452283776329 min interval config: 0 actual interval: 3884
,I/CheckinService( 6600): Checkin interval check for package: unspecified last checkin: 1452283776329 min interval config: 0 actual interval: 3892
,I/CheckinService( 6600): Checking schedule, now: 1452283780222 next: 1452283806290
I/CheckinService( 6600): active receiver: disabled
,I/CheckinService( 6600): Checking schedule, now: 1452283780237 next: 1452283806290
I/CheckinService( 6600): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7647 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7519:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7519/cgroup.procs: No such file or directory
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7674 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7539:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7539/cgroup.procs: No such file or directory
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3c67514c
,I/GCoreNlp( 1709): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/ResourcesManager( 7674): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1570): Deferring update until onResume
,I/Babel_SMS( 7674): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7674): MmsConfig.loadMmsSettings
I/Babel_SMS( 7674): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7674): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7674): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7674): MmsConfig.loadFromResources
E/Babel_SMS( 7674): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7674): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7674): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7674): startup - clean
,I/Babel   ( 7674): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7703 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 20.476ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 19.681ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.412ms
,W/VideoCapabilities( 7674): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7674): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7674): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7674): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7674): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7674): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7674): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7674): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7674): onServiceConnected
,W/Babel   ( 7674): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7674): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7562:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/GAv4    ( 7703): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7703):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7703):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7562/cgroup.procs: No such file or directory
,W/GAv4    ( 7703): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7703): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7703): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7703): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7703): Time to load native libraries: 2 ms (timestamps 8530-8532)
I/LibraryLoader( 7703): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7703): Binding Chromium to main looper Looper (main, tid 1) {38990572}
I/LibraryLoader( 7703): Expected native library version number "",actual native library version number ""
,I/chromium( 7703): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7703): Initializing chromium process, singleProcess=true
W/art     ( 7703): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7703): ApplicationContext is null in ApplicationStatus
,W/chromium( 7703): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7703): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7703): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7703): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7703): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7703): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7703): Local Branch: 
I/Adreno-EGL( 7703): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7703): Local Patches: NONE
I/Adreno-EGL( 7703): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7703): Requires BLUETOOTH permission
,I/NSApplication( 7703): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7774 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7591:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7591/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7793 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7625:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7625/cgroup.procs: No such file or directory
,W/ResourcesManager( 7793): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7813 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7674:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7813): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7647:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2858): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7674/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7647/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2858): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2858): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2858): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2858): onServiceConnected()
D/GetNotificationsWS( 2858): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2858): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2858): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2858): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2858): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2858): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7844 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2858): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2858): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2858): publish the event [tag = MOT_OTA event name = LOG]
,I/art     (  880): Explicit concurrent mark sweep GC freed 18168(909KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.774ms total 125.163ms
,D/OtaApp  ( 2858): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2858): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2858): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2858): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2858): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2858): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2858): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2858): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2858): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6733): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1419): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,336
,D/LocationInitializer( 6600): Restart initialization of location
,I/ActivityManager(  880): Killing 7703:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     ( 1709): Explicit concurrent mark sweep GC freed 97002(5MB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 15MB/25MB, paused 1.160ms total 141.846ms
,D/WearableService( 1709): callingUid 10016, callindPid: 1709
,E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29c941f3)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11bb4eb0)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ada5129)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32653cae)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a2c0a4f)
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7703/cgroup.procs: No such file or directory
,E/MDM     ( 1709): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1709): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  880): done {1718a04a, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [9655ms]
,W/GCoreFlp( 1709): No location to return for getLastLocation()
W/FusedLocationProvider( 1709): location=null
,I/art     ( 6573): Explicit concurrent mark sweep GC freed 2793(119KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 459us total 40.919ms
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7884 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7884): Register our PhoneStateListener
,V/SetupWizard( 7884): Connected to Gservices successfully
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7907 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7935 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7952 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7774:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7793:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7774/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7793/cgroup.procs: No such file or directory
,W/ResourcesManager( 7952): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7952): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7952): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7952): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7952): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7952): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7952): MmsConfig.loadFromResources
,E/Babel_SMS( 7952): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7952): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7952): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7952): startup - clean
,I/Babel   ( 7952): deleted: false for 0
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7986 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7952): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7952): Unsupported mime audio/amr-wb-plus
,W/asset   ( 7986): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7986): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7986): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7986): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7952): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7952): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7952): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7952): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7952): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6600): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/VideoCapabilities( 7952): Unrecognized profile 2130706433 for video/avc
,I/UpdateIcingCorporaServi( 7907): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@20b827b new=com.google.android.velvet.VelvetApplication@20b827b
,I/PackageBroadcastService( 6600): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8011 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6600): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 8011): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 7952): onServiceConnected
W/Babel   ( 7952): Attempted to change video mute state without an active call.
,I/UpdateIcingCorporaServi( 7907): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,I/ActivityManager(  880): Killing 7844:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/ResourcesManager( 7952): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7952): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7844/cgroup.procs: No such file or directory
,V/JNIHelp ( 7952): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7952): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7952): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8050 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.603ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 19.352ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.051ms
,I/ActivityManager(  880): Killing 7884:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7884/cgroup.procs: No such file or directory
,D/Finsky  ( 8050): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8050): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8050): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8050): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8050): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8050): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8050): Skipping gmscore version check
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8097 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7935:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_7935/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,D/Finsky  ( 8050): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8050): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 7986:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/Icing   ( 6600): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_7986/cgroup.procs: No such file or directory
,D/Icing   ( 6600): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6600): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 7907:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7907/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 7813:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7813/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 6600): Done disabling old GoogleServicesFramework version
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311311, SEQNUM=4465, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=11501, POWER_SUPPLY_CHARGE_COUNTER=226, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2714): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2714): Disconnected process message: 10, size: 0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1709): disconnect managed GoogleApiClient
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309983, SEQNUM=4467, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=8776, POWER_SUPPLY_CHARGE_COUNTER=282, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2714): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2714): Disconnected process message: 10, size: 0
,V/AlarmManager(  880): send {1bcfcd85, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {962580b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  880): send {f8d2b51, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  880): done {962580b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [20ms]
,V/AlarmManager(  880): done {f8d2b51, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [36ms]
,I/CheckinService( 6600): Checkin interval check for package: unspecified last checkin: 1452283776329 min interval config: 0 actual interval: 42564
,V/AlarmManager(  880): done {1bcfcd85, *alarm*:android.intent.action.TIME_TICK} [58ms]
,I/CheckinService( 6600): Checking schedule, now: 1452283818915 next: 1452283806290
I/CheckinService( 6600): active receiver: enabled
,I/CheckinService( 6600): Preparing to send checkin request
I/EventLogService( 6600): Accumulating logs since 1452283770613
,I/CheckinRequestBuilder( 6600): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6600): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  880): Explicit concurrent mark sweep GC freed 16534(845KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.591ms total 113.822ms
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8140 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8140): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8140): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8140): VM with version 2.1.0 has multidex support
I/MultiDex( 8140): install
I/MultiDex( 8140): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8140): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8140): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8140): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ea327c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8140): Installed default security provider GmsCore_OpenSSL
,D/AuthorizationBluetoothService( 1709): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6600): Restart initialization of location
,D/WearableService( 1709): callingUid 10016, callindPid: 1709
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1709): [216] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1709): No location to return for getLastLocation()
W/FusedLocationProvider( 1709): location=null
,I/art     ( 8140): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8140): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8140): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  311): Instantiating CDM.
I/WVCdm   (  311): CdmEngine::OpenSession
,I/WVCdm   (  311): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  311): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  311): Service_Initialize: starts!
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,E/QSEECOMAPI: (  311): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,D/QSEECOMAPI: (  311): Loaded image: APP id = 3
,D/DrmWidevineDash(  311): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faa000
E/DrmWidevineDash(  311): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faa000
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  311): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: starts! SID=0xbef174e0
,D/DrmWidevineDash(  311): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: starts! randomData=0xb8254838, dataLength=8
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb830b420, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  311): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  311): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  311): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  311): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: starts! deviceID=0xb8338838, idLength=0xbef172b0
,D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  311): PrepareKeyRequest: nonce=3878572121
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8267148
D/DrmWidevineDash(  311): message_length=1591, signature=0xb8267788, signature_length=3203494548
,D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  311): CdmEngine::CloseSession
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  311): L3 Terminate.
D/DrmWidevineDash(  311): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  311): Service_Uninitialize: starts!
D/QSEECOMAPI: (  311): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  311): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  311): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_Terminate: ends! returns 0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/WVCdm   (  311): CdmEngine::OpenSession
I/WVCdm   (  311): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  311): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  311): Service_Initialize: starts!
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,E/QSEECOMAPI: (  311): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,D/QSEECOMAPI: (  311): Loaded image: APP id = 3
D/DrmWidevineDash(  311): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faa000
E/DrmWidevineDash(  311): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4faa000
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  311): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: starts! SID=0xb13ba960
D/DrmWidevineDash(  311): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: starts! randomData=0xb824e250, dataLength=8
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb830b420, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  311): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  311): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  311): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  311): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: starts! deviceID=0xb8338858, idLength=0xb557f730
,D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  311): PrepareKeyRequest: nonce=273657394
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8254748
D/DrmWidevineDash(  311): message_length=1626, signature=0xb81dadc0, signature_length=3042440980
,D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  311): CdmEngine::CloseSession
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  311): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  311): L3 Terminate.
D/DrmWidevineDash(  311): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  311): Service_Uninitialize: starts!
D/QSEECOMAPI: (  311): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  311): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  311): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8191): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8191): dex2oat took 85.075ms (threads: 4)
,I/Adreno-EGL( 8140): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8140): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8140): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8140): Local Branch: 
I/Adreno-EGL( 8140): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8140): Local Patches: NONE
I/Adreno-EGL( 8140): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8140): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8140): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8140): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8140): Local Branch: 
I/Adreno-EGL( 8140): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8140): Local Patches: NONE
I/Adreno-EGL( 8140): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8140): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8140): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8140): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8140): Local Branch: 
I/Adreno-EGL( 8140): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8140): Local Patches: NONE
I/Adreno-EGL( 8140): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8140): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8140): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8140): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8140): Local Branch: 
I/Adreno-EGL( 8140): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8140): Local Patches: NONE
I/Adreno-EGL( 8140): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6600): Classify the device as Phone.
,I/CheckinTask( 6600): Sending checkin request (9604 bytes)
,I/CheckinRequestBuilder( 6600): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6600): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6600): Classify the device as Phone.
,I/CheckinTask( 6600): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6600): Checking schedule, now: 1452283821962 next: 1452884958952
I/CheckinService( 6600): active receiver: disabled
,D/CheckinService( 6600): Recording last checkin time for package unspecified as 1452283821972
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8211 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8211): Register our PhoneStateListener
,V/SetupWizard( 8211): Connected to Gservices successfully
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Killing 8050:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  880): Killing 8011:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_8050/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8011/cgroup.procs: No such file or directory
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8233 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3236ce76
,I/GCoreNlp( 1709): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1570): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8270 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8292 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8097:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_8097/cgroup.procs: No such file or directory
,W/ResourcesManager( 7952): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7952): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8315 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 8211:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8292): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8211/cgroup.procs: No such file or directory
,W/asset   ( 8315): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8315): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8315): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8315): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6600): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6600): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@20b827b new=com.google.android.velvet.VelvetApplication@20b827b
,I/UpdateIcingCorporaServi( 8233): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6600): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8341 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  880): Explicit concurrent mark sweep GC freed 17808(944KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.690ms total 136.929ms
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,W/ResourcesManager( 8341): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8233): UpdateCorporaTask done [took 191 ms] updated apps [took 191 ms] 
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8370 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8140:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_8140/cgroup.procs: No such file or directory
,D/Finsky  ( 8370): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8370): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8370): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8370): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8370): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8370): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8370): Skipping gmscore version check
,D/Finsky  ( 8370): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8370): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 8270:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8270/cgroup.procs: No such file or directory
,I/Icing   ( 6600): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6600): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8315:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8315/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 7952:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7952/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1419): run()
I/Keyboard.Facilitator( 1419): flushDynamicLanguageModels()
,I/ConfigService( 1709): onCreate
,I/ConfigService( 1709): onDestroy
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6733): --= Surplus to requirements =--
I/jxcore-log( 6733): 
I/jxcore-log( 6733): ****TEST TOOK:  ms ****
I/jxcore-log( 6733): 
I/jxcore-log( 6733): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6733): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,D/AndroidRuntime( 8431): 
D/AndroidRuntime( 8431): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8431): CheckJNI is OFF
,D/AndroidRuntime( 8431): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  880): Force stopping com.test.thalitest appid=10429 user=-1: uninstall pkg
,I/ActivityManager(  880): Killing 6733:com.test.thalitest/u0a429 (adj 9): stop com.test.thalitest
,I/WindowState(  880): WIN DEATH: Window{3bb71262 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  880): Client connection lost with reason: 4
,W/PackageSettings(  880): Skipping PackageSetting{3da130f6 com.example.hello/10426} due to missing metadata
,I/ActivityManager(  880):   Force finishing activity ActivityRecord{be6266f u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  880): Spurious death for ProcessRecord{3903a2e0 6733:com.test.thalitest/u0a429}, curProc for 6733: null
,I/ActivityManager(  880): Force stopping com.test.thalitest appid=10429 user=0: pkg removed
I/ActivityManager(  880):   Force finishing activity ActivityRecord{be6266f u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{be6266f u0 com.test.thalitest/.MainActivity t3 f}
,I/art     ( 3382): Explicit concurrent mark sweep GC freed 10117(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/12MB, paused 853us total 41.781ms
,I/Keyboard.Facilitator( 1419): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1419): run()
,I/Decoder ( 1419): createOrResetDecoder
,W/GeofencerStateMachine( 1709): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,D/VoicemailCleanupService( 8292): Cleaning up data for package: com.test.thalitest
I/art     ( 1570): Explicit concurrent mark sweep GC freed 4941(304KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 489us total 116.649ms
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8462 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  880): Explicit concurrent mark sweep GC freed 11202(759KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.518ms total 174.989ms
,I/art     (  880): WaitForGcToComplete blocked for 122.849ms for cause Explicit
,I/ConfigService( 1709): onCreate
,W/asset   ( 8462): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8462): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8462): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1419): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1419): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1419): run()
I/StatsUtilsManager( 1419): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1419): shouldRecordStats() = Too Soon
,I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8486 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
,I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 20.573ms
,I/art     (  880): Explicit concurrent mark sweep GC freed 3392(188KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.608ms total 176.394ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 19.900ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.064ms
,I/ActivityManager(  880): Killing 8233:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/AndroidRuntime( 8431): Shutting down VM
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8233/cgroup.procs: No such file or directory
,I/Launcher( 1570): Deferring update until onResume
,W/ContextImpl( 8486): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6600): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 6600): Reading stored module config
,D/AccountUtils( 6600): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6600): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6600): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 6600): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6600): App measurement is starting up, version: 8489
I/GMPM-SVC( 6600): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1709): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1709): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8521 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/SQLiteDatabase( 6600): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6600): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6600): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6600): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6600): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6600): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6600): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6600): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6600): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6600): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6600): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6600): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6600): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 6600): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6600): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 6600): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 6600): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6600): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6600): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6600): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6600): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6600): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6600): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6600): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6600): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 6600): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 6600): Opened metrics.db in read-only mode
,D/gH_CompatibleDatabase( 6600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 6600): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 6600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,--------- beginning of crash
E/AndroidRuntime( 6600): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6600): Process: com.google.android.gms, PID: 6600
E/AndroidRuntime( 6600): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6600): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6600): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 6600): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6600): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6600): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 6600): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6600): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6600): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6600): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6600): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6600): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6600): Sending signal. PID: 6600 SIG: 9
,E/DropBoxManagerService(  880): Can't write: system_app_crash
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  880): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  880): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  880): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  880): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  880): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  880): 	... 5 more
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
